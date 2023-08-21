# Playwright Snippets Suite🎭

**Note**
- This snippets follows Page object model
- This extension is meant for `Typescript` and `Javascript` language.

## Getting Started
This Visual Studio Code extension adds predefined useful code snippets for 🎭 [Playwright](https://github.com/microsoft/playwright).

### Used tools

- [playwright](https://playwright.dev/) - Playwright is a Node.js library to automate tests cases for variou browsers.
- [@playwright/test](https://playwright.dev/docs/api/class-test) - Playwright Test provides a test function to declare tests and expect function to write assertions.
- [playwright-core](https://www.npmjs.com/package/playwright-core) - This package contains the no-browser flavor of Playwright.

## Requirements

- Visual Studio Code (VS Code) version 1.80.0 or higher.

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

#### Test block
| Snippet                    | Content                        |
| -------------------------- | ------------------------------ |
| `p-td`                     | test.describe()                |
| `p-t`                      | test()                         |
| `p-ts`                     | test.step()                    |
| `p-tbe`                    | test.beforeEach()              |
| `p-tae`                    | test.afterEach()               |
| `p-tba`                    | test.beforeAll()               |
| `p-taa`                    | test.afterAll()                |
| `p-tuse`                   | test.use()                     |

#### Browser actions
| Snippet                    | Content                        |
| -------------------------- | ------------------------------ |
| `p-browser-newContext`     | browser.newContext()           |
| `p-browser-newPage`        | browser.newPage()              |

#### Context actions
| Snippet                    | Content                        |
| -------------------------- | ------------------------------ |
| `p-context-newPage`        | context.newPage()              |
| `p-context-pages`          | context.pages()                |

#### Page actions
| Snippet                    | Content                        |
| -------------------------- | ------------------------------ |
| `p-goto`                   | page.goto()                    |
| `p-clk`                    | page.click()                   |
| `p-dbclk`                  | page.dblclick()                |
| `p-clki`                   | page.nth().click()             |
| `p-chk`                    | page.check()                   |
| `p-uchk`                   | page.uncheck()                 |
| `p-hover`                  | page.hover()                   |
| `p-press`                  | page.press()                   |
| `p-sif`                    | page.setInputFiles()           |
| `p-screenshot-full`        | Full page screenshot           |
| `p-screenshot-element`     | Element screenshot             |
|                            |                                |
| `p-title`                  | page.title()                   |
| `p-url`                    | page.url()                     |
|                            |                                |
| `p-fill`                   | page.fill()                    |
| `p-type`                   | page.type()                    |
| `p-so`                     | page.selectOption()            |
|                            |                                |
| `p-isv`                    | page.isVisible()               |
| `p-ish`                    | page.isHidden()                |
| `p-isc`                    | page.isChecked()               |
| `p-isen`                   | page.isEnabled()               |
| `p-isd`                    | page.isDisabled()              |
| `p-ised`                   | page.isEditable()              |
|                            |                                |
| `p-getattr`                | page.getAttribute()            |
| `p-itxt`                   | page.innerText()               |
| `p-count`                  | page.count()                   |
| `p-focus`                  | page.focus()                   |
| `p-goBack`                 | page.goBack()                  |
| `p-goFwd`                  | page.goForward()               |


#### Page assertion/expect actions
| Snippet                    | Content                        |
| -------------------------- | ------------------------------ |
| `p-etbv`                   | page.toBeVisible()             |
| `p-etbh`                   | page.toBeHidden()              |
| `p-etbe`                   | page.toBeEnabled()             |
| `p-etbd`                   | page.toBeDisabled()            |
| `p-etbc`                   | page.toBeChecked()             |
| `p-etb`                    | expect.toBe()                  |
| `p-etht`                   | expect.toHaveTitle()           |
| `p-etctxt`                 | expect.toContainText()         |
| `p-ethattr`                | expect.toHaveAttribute()       |
| `p-ethc`                   | expect.toHaveCount()           |
| `p-ethtxt`                 | expect.toHaveText()            |
| `p-ethURL`                 | expect.toHaveURL()             |
| `p-ethss`                  | expect.toHaveScreenshot()      |

#### New Advanced Locators
| `p-get-txt`                | page.getByText                 |
| `p-get-r`                  | page.getByRole                 |
| `p-get-l`                  | page.getByLabel                |
| `p-get-ti`                 | page.getByTestId               |
| `p-get-p`                  | page.getByPlaceholder          |
| `p-get-atxt`               | page.getByAltText              |
| `p-get-title`              | page.getByTitle                |
| `p-locator`                | page.locate                    |

#### Page wait actions
| Snippet                    | Content                        |
| -------------------------- | ------------------------------ |
| `p-wf`                     | page.waitFor()                 |
| `p-wfs`                    | page.waitForSelector()         |
| `p-wfls`                   | page.waitForLoadState()        |
| `p-wft`                    | page.waitForTimeout()          |



#### Other actions
| Snippet                    | Content                        |
| -------------------------- | ------------------------------ |
| `p-pam`                    | public async method() {...}    |
| `p-newPage`                | Handle new tab/ page           |
| `p-newPopup`               | Handle popups                  |
| `p-testBlock`              | Complete test block            |
| `p-saveHAR`                | Save HAR file                  |
| `p-route`                  | page.route                     |


## Happy Coding
