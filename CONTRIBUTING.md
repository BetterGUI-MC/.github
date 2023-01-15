# How to contribute

## [Issue Tracker](https://github.com/BetterGUI-MC/Issue-Tracker)

This is where the users report their issue. 

Since it's a community-driven site, you can:
- Create a new ticket to report your issue.
- Request a new feature.
- Answer & resolve other tickets.
- Implement the feature if you are capable.

There is no strict rule on how to create a ticket, but you must:
- Fill all fields on the template if you are reporting an issue.
- Tell all details if you are requesting a new feature.

## [Wiki](https://github.com/BetterGUI-MC/Wiki) ([Site](https://bettergui-mc.github.io/Wiki/))

This contains the tutorials for most components of the project.

It's also a community-driven site, so you can:
- Review the content.
- Fix grammar errors & typos.
- Write more content if you think these tutorials need more details.
- Write new sections if you want to tutor more about the various ways to use the project.

There is also no strict rule on how to contribute to the Wiki. However, if you create a new section (file), you must include it in `SUMMARY.md` (the outline file).

## [BetterGUI](https://github.com/BetterGUI-MC/BetterGUI) ([Javadoc](https://bettergui-mc.github.io/BetterGUI))

This is the main plugin. It serves as a barebone plugin that contains common functions that all servers need, which means a new feature is most likely rejected if it is requested directly to this repository. However, there are exceptions depending on how important that feature is. In this case, the code owners are the one who give the final decision whether the feature can be merged or should be in an addon.

If you contribute to this repository, you must:
- Comment the classes & methods you created in the Javadoc format.
- Follow the code style specified in `.editorconfig`.
  - Use [the Oracle code conventions](https://www.oracle.com/java/technologies/javase/codeconventions-contents.html)
  - Indent & Tab should be 2 spaces.
  - There should be blank lines between sections of the comment block.
  ```java
  /**
   * Description
   * 
   * @param args the argument
   * 
   * @return the return value
   */
  ```

## [Addons](https://github.com/BetterGUI-MC/Addon-List)

Addon is a file that expands the features of the main plugin. If there is a new feature, it will likely be in an Addon.

If you have an idea and want to create an addon, make sure to check [AddonParent](https://github.com/BetterGUI-MC/AddonParent) & [ExampleAddon](https://github.com/BetterGUI-MC/ExampleAddon). These would help you skip the steps to setup your project by doing the dependency and shading part.

If you have made a new addon and want it to be known, you must:
- Create a new Markdown file in the `addon` folder of the Wiki repository and link it to `SUMMARY.md` (check [Wiki](#wiki)).
- Add the addon to the [Addon List](https://github.com/BetterGUI-MC/Addon-List/blob/master/addons.json) with the [appropriate format](https://github.com/BetterGUI-MC/Addon-List#format).
  - You have to provide the link to the source code, the wiki and a direct download link of your addon.

If you modified an addon, you must:
- Update the version of the addon.
- Update the wiki of the addon.
- Request a version update to the [Addon List](https://github.com/BetterGUI-MC/Addon-List/blob/master/addons.json)
