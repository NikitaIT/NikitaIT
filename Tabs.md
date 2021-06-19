# Tabs

- `tabpanel` should be focusable by tab if not single on page.

Types:

- router-tabs
- form-tabs

## router-tabs

- set `href="#tab-name"`
- open current tab on page loaded
- async/sync dom loaded `tabpanel`

But what about `rolling tabindex`?
When `tablist` should be `nav`?


## form-tabs
Home	Moves focus to the first tab and activates it.
End	Moves focus to the last tab and activates it.
Delete
- `tablist` extends `rolling tabindex` behavior
- pre-loaded `tabpanels`
- `tab` should be button

**Warn:** pure [css tabs](https://codepen.io/NikitaIT/pen/YzZggxz) by `#tab-name:checked ~ .section .tablist-name { display: block; }` not accessible. 
But css is fast, what about mobile?

**Warn:** `tablist` not extends full `radio` behavior, only vertical or horisontal arrows behavior.

**Exemple:** [wai-aria-practices/tabs](https://www.w3.org/TR/wai-aria-practices-1.1/examples/tabs/tabs-1/tabs.html)
