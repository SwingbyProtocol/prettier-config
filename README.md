A common Prettier config used in Swingby's projects.

## Quick start

1. Install Prettier and this package.

   ```bash
   yarn add --dev prettier @swingby-protocol/prettier-config
   ```

2. Add the follow config file at the root of your project.

   ```js
   // prettier.config.js
   module.exports = require('@swingby-protocol/prettier-config');
   ```

3. (Optional) Add the following config for EditorConfig.

   ```editorconfig
   # .editorconfig

   root = true

   [*]
   indent_style = space
   indent_size = 2
   end_of_line = lf
   charset = utf-8
   trim_trailing_whitespace = true
   insert_final_newline = true

   [*.md]
   trim_trailing_whitespace = false
   ```
