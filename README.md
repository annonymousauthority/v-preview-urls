# Vue URL Previewer

The vue3 component for previewing on webpages.

## Installation

```
npm i v-preview-urls
```

In Main.js

```
import vPreview from 'v-preview-urls'
import "v-preview-urls/dist/v-preview-urls.css"

createApp(App).use(vPreview)
```

In Vue Component

```
<v-urls :class="classdata" :url="url"/>
```

### Note

`This is a semi-styled preview card and you can style the parts of the card outlook but not the content`
`You can also use this in vite and nuxt projects also.`

#### Limitations

The package currently does not support previewing social media urls.

### Contributions

This package is open source and contributors are welcomed.

#### Reporting Issues

Found a problem? Want a new feature? First of all, see if your issue or idea has already been reported. If don't, just open a new clear and descriptive issue.

#### Submitting pull requests

Pull requests are the greatest contributions, so be sure they are focused in scope and do avoid unrelated commits.
Fork it!
Clone your fork: git clone https://github.com/annonymousauthority/v-preview-urls
Navigate to the newly cloned directory: cd v-preview-urls
Create a new branch for the new feature: git checkout -b my-new-feature
Install the tools necessary for development: yarn
Make your changes.
Commit your changes: git commit -am 'Add some feature'
Push to the branch: git push origin my-new-feature
Submit a pull request with full remarks documenting your changes

### License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

### Support

You can contact me via email augustinerepos@gmail.com or connect with me via twitter: https://twitter.com/_talentseeker.
