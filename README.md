# Vue URL Previewer V0.5

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

#### Note

`This is a semi-styled preview card and you can style the parts of the card outlook but not the content`
`You can also use this in vite and nuxt projects also.`

#### Limitations

The package currently does not support previewing social media urls. The project is open for pull requests and contributions on github

### Support

You can contact me via email augustinerepos@gmail.com or connect with me via twitter: https://twitter.com/_talentseeker.
