# Simple SVG "search" icon

SVG in HTML to become a "Search" icon button, with no text

Three sizes: 42px, 28px, 16px

Examples both for a `<button>` and `<input type=submit>`

Special, unneeded thanks to [Method Draw](https://editor.method.ac/) at [github.com/duopixel](https://github.com/duopixel/Method-Draw).

| **42px** :

```html
<svg width="42" height="42" xmlns="http://www.w3.org/2000/svg">
	<ellipse stroke="#000" stroke-width="5" ry="14" rx="14" id="svg_1" cy="17" cx="17" fill="none" />
	<line stroke="#000" stroke-width="5" id="svg_3" y2="38" x2="38" y1="26" x1="26" fill="none" />
</svg>
```

| **28px** :

```html
<svg width="28" height="28" xmlns="http://www.w3.org/2000/svg">
	<ellipse stroke="#000" stroke-width="3" ry="10" rx="10" id="svg_1" cy="12" cx="12" fill="none"/>
	<line stroke="#000" stroke-width="3" id="svg_3" y2="27" x2="27" y1="18" x1="18" fill="none"/>
</svg>
```

| **16px** :

```html
<svg width="16" height="16" xmlns="http://www.w3.org/2000/svg">
	<ellipse stroke="#000" stroke-width="2" ry="5" rx="5" id="svg_1" cy="7" cx="7" fill="none" />
	<line stroke="#000" stroke-width="2" id="svg_3" y2="15" x2="15" y1="10" x1="10" fill="none" />
</svg>
```

| **HTML `input`** : (28px)

```html
<label style="cursor:pointer;">

	<svg width="28" height="28" xmlns="http://www.w3.org/2000/svg">
		<ellipse stroke="#000" stroke-width="3" ry="10" rx="10" id="svg_1" cy="12" cx="12" fill="none" />
		<line stroke="#000" stroke-width="3" id="svg_3" y2="27" x2="27" y1="18" x1="18" fill="none" />
	</svg>
	
	<input type="submit" value="Search" hidden>
</label>
```

| **HTML `button`** : (28px)

```html
<button type="submit">

	<svg width="28" height="28" xmlns="http://www.w3.org/2000/svg">
		<ellipse stroke="#000" stroke-width="3" ry="10" rx="10" id="svg_1" cy="12" cx="12" fill="none" />
		<line stroke="#000" stroke-width="3" id="svg_3" y2="27" x2="27" y1="18" x1="18" fill="none" />
		
	</svg>
</button>
```

