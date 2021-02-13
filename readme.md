# awesome-i18n [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of i18n tools, i18n libraries, localization software, localization programs and translation management systems.


## 📦 Contents

- [👩‍🎓 Acronyms and keywords](#-acronyms-and-keywords)
- [🕵️ SEO i18n](#%EF%B8%8F-seo-i18n)
- [📚 Libraries](#-libraries)
- [⚛️ React localization](#%EF%B8%8F-react)
- [👩‍💻  Tools & Services](#-tools-and-services)
- [📅 Dates & Times](#-dates-and-times)
- [📞 Telephone](#telephone)
- [📒 Blog posts & articles](#-blog-posts-articles--others)
- [🦮 Guides](#-guides)
- [💭 Community Tips & tricks](#-community-tips--tricks)
- [✍️ Translation agencies](#%EF%B8%8F-translation-agencies)
- [🦾 Automated translations](#-automated-translations)
- [🍿 Videos](#-videos)

## 👩‍🎓 Acronyms and keywords

### 🧐 Acronyms
* i18n - internationalization
* l10n - localization
* xl8 - group of [translation management systems](#translation-management-system)
* t9n - translation
* g11n - globalization
* m17n - multilingualization
* ICU - International Components for Unicode
* TMS - translation management system
* GMS - globalization translation system (same thing as TMS)

### 🔑 Keywords
* translation key - element in source code which is used by i18n library to replace it with translation message
* translation - translated text or message


## 🕵️ SEO i18n 

* [What is 'hreflang'](https://simplelocalize.io/blog/posts/what-is-hreflang/)


## 📚 Libraries

### JavaScript

* [ECMAScript Internationalization API](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl) documentation what standard `intl` object in JS can do.
* [Facebook FBT](https://github.com/facebook/fbt) FBT is an internationalization framework for JavaScript designed to be not just powerful and flexible, but also simple and intuitive
* [js-lingui](https://github.com/lingui/js-lingui) A readable, automated, and optimized (5kb) internationalization
* [Globalize](https://github.com/jquery/globalize) library for i18n that leverages the official Unicode CLDR JSON data
* [Intl.js](https://github.com/andyearnshaw/Intl.js) implementation of the ECMAScript Internationalization API
* [Jed](http://slexaxton.github.io/Jed/) Gettext Style i18n
* [FormatJS](https://formatjs.io) internationalize your web apps on the client & server
- [FormatJS CLI](https://formatjs.io/docs/tooling/cli/) Extract messages from project with FormatJS library
* [googlei18n/libphonenumber](https://github.com/googlei18n/libphonenumber) Google's common Java, C++ and JavaScript library for parsing, formatting, and validating international phone numbers
* [International Telephone Input](http://jackocnr.com/intl-tel-input.html) plugin for entering and validating international telephone numbers. 
* [lisan.js](http://lisanjs.com) fast and small i18n library
* [Polyglot.js](http://airbnb.io/polyglot.js/) Make your application speak multiple languages
* [c-3po.js](http://c-3po.js.org) library for translations based on ES6 template literals
- [i18n Ally](https://github.com/antfu/i18n-ally) - Extension for VSCode, all in one about i18n.
* [Angular NGX Translate](http://www.ngx-translate.com) Angular translation library
- [npm i18n](https://www.npmjs.com/package/i18n) - Lightweight simple translation module with dynamic json storage.
* [vue i18n](https://kazupon.github.io/vue-i18n/) Vue I18n is internationalization plugin for Vue.js
- [MDN i18n](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/API/i18n) - Functions to internationalize your browser extension. You can use these APIs to get localized strings from locale files packaged with your extension.
- [Quasar I18n](https://quasar.dev/options/app-internationalization) - App internationalization (i18n) in Quasar framework.
- [eo-locale](https://github.com/ibitcy/eo-locale) Elegant lightweight library based on Internationalization API


### ⚛️ React

* [bloodyowl/react-translate](https://github.com/bloodyowl/react-translate) Internationalization for react
- [react-native-localize](https://github.com/zoontek/react-native-localize) A toolbox for your React Native app localization
* [FormatJS](https://formatjs.io) internationalize your web apps with react-intl library
- [FormatJS CLI](https://formatjs.io/docs/tooling/cli/) Extract messages from project with FormatJS library
- [react-localization](https://github.com/stefalda/react-localization) Simple module to localize the React interface using the same syntax used in the ReactNativeLocalization module.
- [react-i18nify](https://github.com/sealninja/react-i18nify) Simple i18n translation and localization components and helpers for React
- [react-persian](https://github.com/evandhq/react-persian) react-persian is a set of react components for Persian localization
* [i18next](http://i18next.com/) i18next is a full-featured i18n javascript library for translating your web application
- [react-i18next](https://react.i18next.com/) - internationalization framework for React / React Native which is based on i18next
- [next-translate](https://github.com/vinissimus/next-translate) Easy i18n for Next.js +10
- [react-translated](https://github.com/amsul/react-translated) A dead simple way to add complex translations in a React project
- [React-intl hooks](https://github.com/CreateThrive/react-intl-hooks) React-intl-hooks is a small and fast library that you can use to replace Format.js components. 


### Java

* [Thymeleaf](https://www.thymeleaf.org) - modern server-side Java template engine for both web and standalone environments.
* [Spring Messages](https://www.baeldung.com/spring-boot-internationalization) Spring Boot internationalization. LocaleResolver & LocaleChangeInterceptor example usage. 
* [Thymeleaf i18n docs](https://www.thymeleaf.org/doc/tutorials/3.0/usingthymeleaf.html#using-texts) using `th:texts` for translations
* [Spring Boot localization](https://www.baeldung.com/spring-boot-internationalization) Baeldun post about using Spring Messages
* [i18n in Spring Boot](https://stackoverflow.com/questions/36531131/i18n-in-spring-boot-thymeleaf) Stackoverflow thread


### Jekyll

* [jekyll-multiple-languages-plugin](https://github.com/kurtsson/jekyll-multiple-languages-plugin) Jekyll Multiple Languages is an internationalization plugin for Jekyll.
* [jekyll-i18n](https://github.com/liamzebedee/jekyll-i18n) Jekyll i18n is a plugin that enables simplistic multi-language site designs using Jekyll. (not maintained)

### Swift (iOS & macOS)

- [SwiftGoogleTranslate](https://github.com/maximbilan/SwiftGoogleTranslate) - A framework to use cloud translation API by Google in Swift.

### Ruby

* [TwitterCLDR](https://github.com/twitter/twitter-cldr-rb) implementation of the ICU that uses the Common Locale Data Repository to format dates, plurals
- [Ruby I18n](https://guides.rubyonrails.org/i18n.html) - Rails internationalization (i18n) API.

### Python

- [Python-i18n](https://pypi.org/project/python-i18n/) - Python internationalization (i18n) package.
- [deep-translator](https://github.com/nidhaloff/deep-translator) - A flexible free and unlimited (depending on the translator used) library written in Python to translate between different languages in a simple way using multiple translators, it can also be used directly in the prompt.

## 👩‍💻 Tools and services

### 🤖 Localization CLI Tools
- [FormatJS CLI](https://formatjs.io/docs/tooling/cli/) Extract messages from project with FormatJS library
- [simplelocalize-cli](https://simplelocalize.io/docs/cli/i18n-keys-extraction/) Extract translation keys and messages from various different libraries

### ☁️ Translation Management Systems

* [memsource](https://www.memsource.com)
* [localizejs](https://localizejs.com)
- [LocaleApp](https://www.localeapp.com/) - App localization and translation.
* [simplelocalize](https://simplelocalize.io)
- [Crowdin](https://crowdin.com/) - Closed source cloud-based localization service
- [GitLocalize](https://gitlocalize.com/) - Localization platform that syncs with your GitHub repository (sold to alconst)
- [Transifex](https://www.transifex.com/) - Web-based translation platform, globalization management system.
- [Weblate](https://weblate.org/) - Platform for one of the most positive and empowering communities of libre software.
- [Zanata](http://zanata.org/) - Web translation platform for translators and developers to manage localisations.
- [Traduora](https://github.com/traduora/traduora) - A platform for manage translations.

### 🖥 Desktop apps
* [GNU gettext](http://www.gnu.org/software/gettext/) tool for adding native language support to applications
- [RTranslator](https://github.com/niedev/RTranslator) - simultaneous translator app for Android based on Google's API.
- [Crow Translate](https://github.com/crow-translate/crow-translate) - A simple and lightweight desktop translator. Allows to translate and speak text using Google, Yandex and Bing translate API.
- [Copy Translator](https://github.com/CopyTranslator/CopyTranslator) - Cross-platform app that automatically translate texts when copied in the clipboard
- [Electronjs i18n](https://www.electronjs.org/apps/i18n-manager) - Cross-platform i18n manager
- [OmegaT](https://omegat.org/) - Free translation memory application that works on Windows, macOS and Linux
- [Argos Translate](https://github.com/argosopentech/argos-translate) - Open source offline translation app based on OpenNMT
- [LibreTranslate](https://github.com/uav4geo/LibreTranslate) - self-hosted web application to translate texts


## 📅 Dates and Times

* [MomentJS](https://momentjs.com) JavaScript library for handling times and dates
* [Luxon](https://moment.github.io/luxon/) A powerful, modern, and friendly wrapper for Javascript dates and times
* [Daylight saving time and time zone best practices](http://stackoverflow.com/questions/2532729/daylight-saving-time-and-time-zone-best-practices)
- [date-fns](https://date-fns.org) Modern JavaScript date utility library

## 📞 Telephone

* [Random Phone Number Generator](https://fakenumber.org/) Fake phone number generator
* [googlei18n/libphonenumber](https://github.com/googlei18n/libphonenumber) Google's common Java, C++ and JavaScript library for parsing, formatting, and validating international phone numbers

## 📒 Blog posts, articles & others

* [What is 'hreflang' attribute](https://simplelocalize.io/blog/posts/what-is-hreflang/)
- [Stack Overflow Q&A-1](https://stackoverflow.com/questions/506743/localization-and-internationalization-whats-the-difference) - Localization and internationalization, what's the difference?
- [Top 12 libraries for React localization](https://dev.to/jpomykala/top-12-libraries-for-nextjs-react-apps-and-react-native-apps-for-i18n-and-react-localization-5fi8) Blog post on dev.to about top 12 libraries for react localization
- [Development/Production parity for Rails i18n](https://withatwist.dev/the-12-factor-app-dev-and-prod-parity.html) - Blog post with a warning on using different I18n backends in development/production

## 🦮 Guides
- [Angular and i18n](https://angular.io/guide/i18n) - Angular i18n guide.
- [Message extraction](https://simplelocalize.io/docs/cli/i18n-keys-extraction/) Extracting translation keys from project files. JavaScript, Android, iOS/macOS

## 💭 Community Tips & tricks

- If you have tight layouts, my rough rule of thumb is to double the English text and make sure it fits. Then you will usually have enough space for translations.
- Russian and German tend to have the longest translations, and the longest words. Get familiar with the shy-hyphen ­ character. You put it in the words html and it will only break the word/show the hyphen when necessary. Google “online hyphenation tool” so you know the appropriate places to break the word.
- you need to translate numbers with decimals because the period appears as a comma in some languages.
- same goes for percent signs. Sometimes the % shows before the number, and not after. There might be a space between the number and %. It might show as %-KAL in Hungarian.
- Greek question marks look like a semicolon, that one really threw me off when I first saw it.


## ✍️ Translation agencies

[✌️Add your agency](https://github.com/jpomykala/awesome-i18n/issues/new)

## 🦾 Automated translations

* [Gengo](http://gengo.com) Translation is made by real people but you can make an order using API
* [Google Translate](https://translate.google.com)
* [Microsoft Translator](https://www.microsoft.com/en-GB/translator/)
* [DeepL](https://deepl.com)

## 📘 Documetations

* [Google Developers: Internationalization](https://developers.google.com/international/)
* [Common Language Data Repository](http://cldr.unicode.org/) The Unicode CLDR provides key building blocks for software to support the world's languages, with the largest and most extensive standard repository of locale data available.
* [ICU: International Components for Unicode](http://site.icu-project.org/) ICU is a mature, widely used set of C/C++ and Java libraries providing Unicode and Globalization support for software applications.
* [W3C i18n standards](http://www.w3.org/standards/webdesign/i18n)


## 🍿 Videos

#### Internationalis(z)ing Code - Computerphile

![youttube internationalization](youtube-computerphile-internationalization.png)

Link: https://www.youtube.com/watch?v=0j74jcxSunY

#### The Problem with Time & Timezones - Computerphile

![youttube internationalization](youtube-computerphile-timezones.png)

Link: https://www.youtube.com/watch?v=-5wpm-gesOY


## 📢 Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.
