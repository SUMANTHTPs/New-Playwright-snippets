# Playwright Snippets Suite🎭

**Note**
    - This snippets follows POM structure
    - This extension is meant for `typescript` and `javascript` language.

## Getting Started
This Visual Studio Code extension adds predefined useful code snippets for 🎭 [Playwright](https://github.com/microsoft/playwright).

### Used tools

- [playwright](https://playwright.dev/) - Playwright is a Node.js library to automate tests cases for variou browsers.
- [@playwright/test](https://playwright.dev/docs/api/class-test) - Playwright Test provides a test function to declare tests and expect function to write assertions.
- [playwright-core](https://www.npmjs.com/package/playwright-core) - This package contains the no-browser flavor of Playwright.

## Requirements

- Visual Studio Code (VS Code) version 1.60.0 or higher.

## Installation

1. Open **Visual Studio Code**.
2. Go to **Extensions** view by clicking on the Extensions icon in the Activity Bar on the side of the window or using the keyboard shortcut `Ctrl+Shift+X` (Windows/Linux) or `Cmd+Shift+X` (Mac).
3. Search for "Playwright Snippets Suite" in the Extensions view search box.
4. Click on the **Install** button to install the extension.
5. Reload Visual Studio Code to enable the extension.

## Usage

1. Open a **JavaScript** or **TypeScript** file in Visual Studio Code.
2. Start typing one of the predefined snippets (e.g., `p-`) to trigger the code snippet suggestion.
3. Select the desired snippet from the suggestions list, or press `Tab` to insert the snippet directly.
4. Replace placeholders (if any) with your custom test code.

### Snippets List

- `p-td`: test.describe Block

- `p-t`: test Block

- `p-ts`: test.step Block

- `p-tbe`: test.beforeEach

- `p-tae`: test.afterEach

- `p-tba`: test.beforeAll

- `p-taa`: test.afterAll

- `p-clk`: page click

- `p-clki`: click selector with index

- `p-title`: Get page title

- `p-url`: Get page url

- `p-pam`: Create asynchronous method

- `p-etbv`: Expect to be visible

- `p-etbh`: Expect to be hidden

- `p-etb`: Expect to be

- `p-etbc`: Expect to be checked

- `p-etbe`: Expect to be enabled

- `p-etbd`: Expect to be disabled

- `p-wf`: page waitFor

- `p-wfs`: waitForSelector

- `p-wfls`:   waitForLoadState

- `p-wft`:    waitForTimeout

- `p-fill`:   fill input

- `p-type`:   type input

- `p-isv`:    Selector isVisible()

- `p-ish`:    Selector isHidden()

- `p-isen`:   Selector isEnabled()

- `p-isd`:    Selector isDisabled()

- `p-isc`:    Selector isChecked()

- `p-ised`:   Selector isEditable()
