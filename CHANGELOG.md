# Changelog

## Next
Fixed:
- 🐛 `rad-tabs` now yields the correct property for the active tab id (`activeId`)

## 1.2.0 (02-07-2017)
Added:
- ✨ `rad-tabs` now yields its `activeTab` state
- ✨ `rad-drawer` now yields its `hidden` state
- ✨ `rad-card` now accepts the following new properties for better customization:
  - `cardClassNames` (applies to the root component element)
  - `cardBodyClassNames` (applies to the body subcomponent root element)
  - `cardFooterClassNames` (applies to the footer subcomponent root element)
  - `cardTitleClassNames` (applies to the title subcomponent root element)
- ✨ `rad-card` and its children now support binding `data-test` attributes
- ✅ Tests added to verify custom classNames are properly passed through to `rad-card`'s subcomponents
- 📝 Guides updated with new passed and yielded props

## 1.1.1 (02-07-2017)
Fixed:
- 🐛 Added missing `tabButtonClassNames` property to `rad-tabs`

## 1.1.0 (02-07-2017)
Added:
- ✨ `rad-tabs` now accepts the following new properties for better customization:
  - `buttonStyleClassNames` (applies to the tab bar `<ul>` element)
  - `tabClassNames` (applies to tab item `<li>` elements in the tab bar)
  - `tabListClassNames` (applies to the tab bar `<ul>` element)
- ✅ Tests added to verify custom classNames are properly passed through

## 1.0.1 (02-06-2017)

Fixed:
- 🐛 Rad modals no longer throw errors about bad aria-headers when `removeFromDomOnClose` is set to `true`

## 1.0.0 (02-05-2017)
- 🎉 Initial Release!
