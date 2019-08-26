# css-toolkit
Collecting useful CSS

##

Used this to kill scrollbars in UI
```css
.no-scrollbars::-webkit-scrollbar {
	width: 0 !important;
    }
.no-scrollbars, .no-scrollbars * {
	overflow: -moz-scrollbars-none;
	-ms-overflow-style: none;
	overflow: hidden !important;
}
```
