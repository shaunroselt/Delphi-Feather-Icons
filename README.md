# Delphi Feather Icons (.SVG)

The [Feather Icons library](https://feathericons.com/) to use within Delphi.

<p align="center">
  <a href="https://v5.getbootstrap.com/">
    <img src="https://github.com/shaunroselt/Delphi-Feather-Icons/assets/5418178/ff4e2225-595f-4035-a2db-434bd2d2175c" alt="Bootstrap logo" width="200">
  </a>
</p>
<p align="center">
  Open source SVG icon library with over 250 icons.
</p>

![Feather Icons preview](https://github.com/shaunroselt/Delphi-Feather-Icons/assets/5418178/34663c13-51d4-4b48-8b0b-fc457fa7e0c3)



## Usage

### SVG Code

```pascal
uses uFeatherIcons

...

// Returns SVG Code
var HomeIconSVG := GetFeatherIcon('home');
var TelevisionIconSVG := GetFeatherIcon('tv');
var BellIconSVG := GetFeatherIcon('bell');

// Returns SVG Code with Width/Height set to 24
var HomeIconSVG := GetFeatherIcon('home', 24);
var TelevisionIconSVG := GetFeatherIcon('tv', 24);
var BellIconSVG := GetFeatherIcon('bell', 24);

// Returns SVG Code with Width/Height set to 24 and color set to purple (#800080):
var HomeIconSVG := GetFeatherIcon('home', 24, 'purple');
var TelevisionIconSVG := GetFeatherIcon('tv', 24, '#800080');
var BellIconSVG := GetFeatherIcon('bell', 24, 'purple');
```

### SVG Path Data

```pascal
uses uFeatherIcons

...

// Returns SVG Path Data Text:
var HomeIconSVGPathData := GetFeatherIconPathData('home');
var TelevisionIconSVGPathData := GetFeatherIconPathData('tv');
var BellIconSVGPathData := GetFeatherIconPathData('bell');

// Returns SVG Path Data Text with Width/Height set to 24:
var HomeIconSVGPathData := GetFeatherIconPathData('home', 24);
var TelevisionIconSVGPathData := GetFeatherIconPathData('tv', 24);
var BellIconSVGPathData := GetFeatherIconPathData('bell', 24);

// Returns SVG Path Data Text with Width/Height set to 24 and color set to purple (#800080):
var HomeIconSVGPathData := GetFeatherIconPathData('home', 24, 'purple'); 
var TelevisionIconSVGPathData := GetFeatherIconPathData('tv', 24, '#800080'); 
var BellIconSVGPathData := GetFeatherIconPathData('bell', 24, 'purple'); 
```

### SVG Base64 Image

```pascal
uses uFeatherIcons

...

// Returns SVG Base64 Image
var HomeIconSVGBase64 := GetFeatherIconBase64('home');
var TelevisionIconSVGBase64 := GetFeatherIconBase64('tv');
var BellIconSVGBase64 := GetFeatherIconBase64('bell');

// Returns SVG Base64 Image with Width/Height set to 24
var HomeIconSVGBase64 := GetFeatherIconBase64('home', 24);
var TelevisionIconSVGBase64 := GetFeatherIconBase64('tv', 24);
var BellIconSVGBase64 := GetFeatherIconBase64('bell', 24);

// Returns SVG Base64 Image with Width/Height set to 24 and color set to purple (#800080):
var HomeIconSVGBase64 := GetFeatherIconBase64('home', 24, 'purple');
var TelevisionIconSVGBase64 := GetFeatherIconBase64('tv', 24, '#800080');
var BellIconSVGBase64 := GetFeatherIconBase64('bell', 24, 'purple');
```

Other ways to use Feather Icons: [https://github.com/feathericons/feather](https://github.com/feathericons/feather)

## License

- Feather Icons are free and open source ([MIT](https://github.com/feathericons/feather/blob/main/LICENSE)).

---

## Other Delphi Icon Libraries
- [Bootstrap Icons](https://github.com/shaunroselt/Delphi-Bootstrap-Icons)
- [Font Awesome Icons](https://github.com/shaunroselt/Delphi-Font-Awesome-Icons)
