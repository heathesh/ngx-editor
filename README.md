# NgxEditor

<p align="center">
  <a href="https://github.com/Sibiraj-S/ngx-editor">
   <img src="https://raw.githubusercontent.com/Sibiraj-S/ngx-editor/master/src/assets/icons/ngx-editor.png" alt="ngxEditor">
  </a>
</p>
<p align="center">A Simple WYSIWYG Editor for Angular2+ Applications.</p>
<p align="center">
  <a href="https://travis-ci.org/Sibiraj-S/ngx-editor">
    <img alt="Build Status" src="https://travis-ci.org/Sibiraj-S/ngx-editor.svg?branch=master">
  </a>
  <a href="https://www.npmjs.com/package/ngx-editor">
    <img alt="npm version" src="https://img.shields.io/npm/v/ngx-editor.svg">
  </a>
  <a href="https://www.npmjs.com/package/ngx-editor">
    <img alt="npm" src="https://img.shields.io/npm/dm/ngx-editor.svg">
  </a>
  <a href="https://github.com/Sibiraj-S/ngx-editor/blob/master/LICENSE">
    <img alt="licence" src="https://img.shields.io/npm/l/ngx-editor.svg">
  </a>
</p>

## Getting Started

### Installation

Install via Package managers such as [npm][npm] or [yarn][yarn]

```bash
npm install ngx-editor --save
# or
yarn add ngx-editor
```

### Usage

Import `ngx-editor` module

```typescript
import { NgxEditorModule } from 'ngx-editor';

@NgModule({
  imports: [ NgxEditorModule ]
})
```

Import [font-awesome](https://github.com/FortAwesome/Font-Awesome) into your application

Then in HTML

```html
<app-ngx-editor [placeholder]="'Enter text here...'" [spellcheck]="true" [(ngModel)]="htmlContent"></app-ngx-editor>
```

For `ngModel` to work, You must import `FormsModule` from `@angular/forms`

### Documentation

Check [wiki][wiki] for more information

[npm]: https://www.npmjs.com/
[yarn]: https://yarnpkg.com/lang/en/
[github]: https://sibiraj-s.github.io/
[wiki]:https://github.com/Sibiraj-S/ngx-editor/wiki/ngxEditor
