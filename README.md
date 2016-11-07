# Tasks for M2JS Project

## Developing custom npm packages

### 1. Task
* use [1.angular2-protractor-jasmine-ts-seed](https://github.com/M2JS/1.angular2-protractor-jasmine-ts-seed)
* look at [weird-reporter](https://github.com/M2JS/weird-reporter) configuration in [protractor.config.ts](https://github.com/M2JS/1.angular2-protractor-jasmine-ts-seed/blob/master/protractor.config.ts)
* use [excel4node](https://www.npmjs.com/package/excel4node) package and develop your custom xlsx reporter
* publish you reporter to github
* publish configured 1.angular2-protractor-jasmine-ts-seed to github and sent lick on it

### 2. Task
* based on **1. Task**, develop html reporter (be free to use node core or any npm packages you wish)
* you should add screenshot capturing after each tests execution (no matter failed or passed)
* save screenshots for local folder (where you save report itself)
* html reporter should show this screenshots
* [materials](https://github.com/M2JS/materials/blob/master/TAKESCREENSHOT.md)

## Practise in TypeScript Automation

* [materials](https://github.com/M2JS/materials/blob/master/SCROLLING.md) to avoid protractor failure when required element is out of view

### 1. Task (Jasmine)
* use [1.angular2-protractor-jasmine-ts-seed](https://github.com/M2JS/1.angular2-protractor-jasmine-ts-seed) as seed,
<br/>or your own project that you build before in scope of **Developing custom npm packages**
* create E2E for https://www.epam.com/

| Scenario | Description | Acceptance criteria |
|----------|-------------|---------------------|
| Header navigation | Check that Header navigation links works | after you click on the link, you should be redirected on the correct page |
| Job search | Check that search works on https://www.epam.com/careers | 1. Check that autocomplete for "JavaScript" correct; <br/> 2. Check that search results for "JavaScript" are correct |

### 2. Task (Cucumber)
* use [2.angular2-protractor-cucumber-ts-seed](https://github.com/M2JS/2.angular2-protractor-cucumber-ts-seed) as seed
* create E2E for https://www.epam.com/

| Scenario | Description | Acceptance criteria |
|----------|-------------|---------------------|
| Header navigation | Check that Header navigation links works | after you click on the link, you should be redirected on the correct page |
| Job search | Check that search works on https://www.epam.com/careers | 1. Check that autocomplete for "JavaScript" correct; <br/> 2. Check that search results for "JavaScript" are correct |
* use two implementation: basic and "cucumber-tsflow" for steps mapping

### 3. Task
* based on **Practise in TypeScript Automation** > **2. Task (Cucumber)** , implement report generator
* your report generator should be:
<br/> 1. published to GitHub
<br/> 2. added to your tests project via package.json
<br/> 3. functionality should be available through gulp
<br/> 4. for html report each test (passed and failed) should have screenshot
* **Help**:
<br/> some initial implementation and readme you can find here: [awesome-report-generator](https://github.com/M2JS/awesome-report-generator)
<br/> example of configuration, please find in [README](https://github.com/M2JS/2.angular2-protractor-cucumber-ts-seed/blob/master/README.md) - **Generate tests reports**
* [materials](https://github.com/M2JS/materials/blob/master/GETIMAGEFROMDECODEDSTRING.md)