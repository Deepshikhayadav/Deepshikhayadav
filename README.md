### Hi There 👋
### Welcome to my Github  👩‍💻💻

- 📱 Mobile App developer.
- 👩🏻‍ 💻 I’m currently working on ❤️Android 🔥Kotlin ❤️Java ❤️Firebase ❤️Rest API!
- 👯 I’m looking to collaborate on Android
- 🤔 I’m looking for help with AWS, Machine learning
- 💬 Ask me about kotlin, java, firebase, room, Rest Api

### 📊 Github Stats

<img src="https://github-readme-stats.vercel.app/api?username=deepshikhayadav&count_private=true&show_icons=true&theme=highcontrast&include_all_commits=true" alt="Deepshikha yadav |Stats" />
  
![GitHub Activity Graph](https://activity-graph.herokuapp.com/graph?username=deepshikhayadav)  

  ### 🤠Used Languages
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=deepshikhayadav&layout=compact)](https://github.com/deepshikhayadav/github-readme-stats"/>

---
### GitHub Streak
  [![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=deepshikhayadav&theme=dark)](https://deepshikhayadav.github.io)
  


![Profile views](https://gpvc.arturio.dev/deepshikhayadav)  
  
  ## 🔗 Know more about me 
[![Mail](https://img.shields.io/badge/-Say%20Hi!-black?style=for-the-badge&logo=gmail)](mailto:deepshikhayadav2000@gmail.com)
[![Twitter](https://img.shields.io/badge/-Twitter-black?style=for-the-badge&logo=twitter)](https://twitter.com/Deepshi83711299)
[![Linkedin](https://img.shields.io/badge/-LinkedIn-black?style=for-the-badge&logo=Linkedin)](https://www.linkedin.com/in/deepshikha-yadav-27-10/)
<!--https://stackoverflow.com/users/12636730/deepshikha-yadav?tab=topactivity-->

[![GitHub deepshikhayadav](https://img.shields.io/github/followers/deepshikhayadav?label=follow&style=social)](https://github.com/deepshikhayadav)

<link rel="stylesheet" href="/path/to/cssIcons.css" />

<!-- add the "svg-icon-bg" class in addition the desired "iconNAME" class -->
<span class="svg-icon-bg iconBold"></span>

<!-- the icon's color matches the "currentColor", so changing the "color" property will change the icon color -->
<span class="svg-icon-bg iconFire" style="color: red;"></span>

<!-- add the "native" class to get native styles; these do not respect "currentColor" changes -->
<span class="svg-icon-bg iconFaceMindBlown native"></span>
```

You can add support for more CSS icons my editing the `src/cssIcons.json` file. Supported formats:
* the name of the icon as a string (e.g. `"Bold"`)
* an object with the following properties:
  * `name` - the name of the icon (e.g. `"Bold"`)
  * `css` - arbitrary css to add to the icon class (e.g. `"width: 14px; height: 14px;"` )

## Using the front-end helper for prototyping

**Note: This is not intended to be used in production.**

If you include the `index.js` within your prototype’s `body` element (`<script src="https://unpkg.com/@stackoverflow/stacks-icons"></script>`) you can render Stacks Icons in the browser using only the following format:

```html
<svg data-icon="FaceMindBlown" class="native"></svg>
<svg data-spot="Search"></svg>
```

This package looks out for elements that look like `svg[data-icon]`. If the icon doesn’t exist in Stacks, it will throw you an error in console. Anything in the `class=""` attribute will be passed to the included SVG e.g., `native`

### Regex for replacing with `@Svg` helper

This might be useful if you want to convert a large prototype to use the Razor helper.

Find

```
<svg data-icon="(.+?)" class="(.+?)"></svg>
```
