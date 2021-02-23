<h1 class="capitalize">COMD2451</h1>
<h2 class="capitalize center">CSS Fonts</h2>

---

<section class="section">
	<h2 class="sentence">The font shorthand property</h2>

We ***will*** be ***using*** the `font shorthand property` to ***style*** `fonts` with some ***new*** `font properties` and their ***corresponding values***.

The `font property` is `shorthand` for:

+ `font-style`: ***specifies*** the `font style` for a `text`.

+ `font-variant`: ***specifies*** whether or not a `text` ***should*** be ***displayed*** in a `small-caps font`.

+ `font-weight`: ***sets*** how ***thick*** or ***thin*** `characters` in `text` ***should*** be ***displayed***.

+ `font-size/line-height`: the `font-size property` ***sets*** the `size` of a `font`. The `line-height property` ***specifies*** the `height` of a `line`.

+ `font-family`: ***specifies*** the `font` for an `element`.

The `font-size` and `font-family` ***values*** are `required`. If ***one*** of the ***other*** `values` is ***missing***, their ***default value*** is `used`.

</section>

---

<section class="section">
	<h2 class="sentence">The font-style property</h2>

The `font-style property` ***specifies*** the `font style` for a `text`.

The `font-style` ***accepts*** the ***following*** `values`:

+ `normal`: The `browser` ***displays*** a ***normal*** `font style`. This is the ***default*** `value`.

+ `italic`: The `browser` ***displays*** an `italic font style`.

+ `oblique`: The `browser` ***displays*** an `oblique font style`.

+ `initial`: ***Sets*** the `font-style property` to its ***default*** `value`.

+ `inherit`: ***Inherits*** the `font-style property` ***from*** its `parent element`.

<aside>
	Note: visit the [CSS font-style Property](https://www.w3schools.com/cssref/pr_font_font-style.asp) page on w3schools to show the students live examples.
</aside>

</section>

---

<section class="section">
	<h2 class="sentence">The font-variant property</h2>

The `font-variant property` ***specifies*** whether or not a `text` ***should*** be ***displayed*** in a `small-caps font`.

In a `small-caps font`, ***all*** `lowercase letters` are ***converted*** to `uppercase letters`. ***However***, the ***converted*** `uppercase letters` ***appear*** in a ***smaller*** `font size` than the ***original*** `uppercase letters` in the `text`.

The `font-variant property` ***accepts*** the ***following*** `values`:

+ `normal`: The `browser` ***displays*** a `normal font`. This is the ***default*** `value`.

+ `small-caps`: The `browser` ***displays*** a `small-caps font`.

+ `initial`: ***Sets*** the `font-variant property` to its ***default*** `value`.

+ `inherit`: ***Inherits*** the `font-variant property` from its `parent element`.

<aside>
	Note: Visit the [CSS font-variant Property(https://www.w3schools.com/cssref/pr_font_font-variant.asp) page on w3schools.
</aside>

</section>

---

<section class="section">
	<h2 class="sentence">The font-weight property</h2>

The `font-weight property` ***sets*** how `thick` or `thin` ***characters*** in `text` should be ***displayed***.

The `font-weight property` ***accepts*** the ***following*** `values`:

+ `normal`: ***Defines*** `normal characters`. This is the ***default*** `value`.

+ `bold`: ***Defines*** `thick characters`.

+ `bolder`: ***Defines*** `thicker characters`.

+ `lighter`: ***Defines*** `lighter characters`.

+ `100 - 900`: ***Defines*** from `thin` to `thick characters`. `400` is the ***same*** as `normal`, and `700` is the ***same*** as `bold`.

+ `initial`: ***Sets*** the `font-weight property` to its ***default*** `value`.

+ `inherit`: ***Inherits*** the `font-weight property` from its `parent element`.

</section>

---

<section class="section">
	<h2 class="sentence">The font-size/line-height properties</h2>

The `font-size property` ***sets*** the `size` of a `font`. In the `font shorthand property`, it is ***defined along*** with the `line-height`, which ***sets*** the `height` of a `line`.

the `font-size` ***accepts*** the ***following*** `values`:

+ `medium`: ***Sets*** the `font-size` to a `medium height`. This is the ***default*** `value`.

+ `xx-small`: ***Sets*** the `font-size` to an `xx-small` ***size***.

+ `x-small`: ***Sets*** the `font-size` to an `extra small` ***size***.

+ `small`: ***Sets*** the `font-size` to a `small` ***size***.

+ `large`: ***Sets*** the `font-size` to a `large size`.

+ `x-large`: ***Sets*** the `font-size` to an `extra large` ***size***.

+ `xx-large`: ***Sets*** the `font-size` to an `xx-large` ***size***.

+ `smaller`: ***Sets*** the `font-size` to a `smaller size` ***than*** the `parent element`.

+ `larger`: ***Sets*** the `font-size` to a `larger size` ***than*** the `parent element`.

+ `length`: ***Sets*** the `font-size` to a `fixed size` in `px`, `cm`, etc.

+ `%`: ***Sets*** the `font-size` to a `percent` of the `parent element`'s `font size`.

+ `initial`: ***Sets*** the `font-size property` to its ***default*** `value`.

+ `inherit`: ***Inherits*** the `font-size property` from its `parent element`.

<aside class="notes">
	Note: visit the [CSS font-size Property](https://www.w3schools.com/cssref/pr_font_font-size.asp) page on w3schools to show the students live examples.
</aside>

</section>

---

<section class="section">
	<h2 class="sentence">The font-family property</h2>

The `font-family property` ***specifies*** the `font` for an `element`.

The `font-family property` can ***hold several*** `font names` as a `"fallback"` ***system***. If the `browser` does ***not*** `support` the ***first*** font, it ***tries*** the ***next*** `font`.

There are ***two*** `types` of `font family names`:

+ `family-name` - The ***name*** of a `font-family`, like `"times"`, `"courier"`, `"arial"`, etc.

+ `generic-family` - The ***name*** of a `generic-family`, like `"serif"`, `"sans-serif"`, `"cursive"`, `"fantasy"`, `"monospace"`.

***Start*** with the `font` you ***want***, and ***always*** end with a `generic family`, to ***let*** the `browser` ***pick*** a ***similar*** `font` in the `generic family`, if ***no other*** `fonts` are ***available***.

If a `font name` ***contains*** `white-space`, it ***must*** be `quoted`. ***Single quotes*** `must` be `used` ***when using*** the `"style"` **attribute** in `HTML`.

The `font-family property` ***accepts*** the ***following*** `values`:

+ `family-name/generic-family`: A ***prioritized list*** of `font family names` and/or `generic family names`.

+ `initial`: ***Sets*** the `font-family property` to its ***default*** `value`.

+ `inherit`: ***Inherits*** the `font-family property` ***from*** its `parent element`.

<aside class="notes">
	Note: visit the [CSS font-family Property](https://www.w3schools.com/cssref/pr_font_font-family.asp) page on w3schools to show the students live examples.
</aside>

</section>

---

<section class="section">
	<h2 class="sentence">CSS Fonts</h2>

***Choosing*** the ***right*** `font` for your `website` is ***important***!

***Choosing*** the ***right*** `font` has a ***huge impact*** on ***how*** the `readers` ***experience*** a `website`.

The ***right*** `font` can ***create*** a `strong identity` for your ***brand***.

***Using*** a `font` that is ***easy*** to ***read*** is ***important***. The `font` ***adds value*** to your `text`. It is ***also*** `important` to ***choose*** the ***correct*** `color` and `text size` for the `font`.

</section>

---

<section class="section">
	<h2 class="sentence">Generic Font Families</h2>

In `CSS` there are ***five*** `generic font families`:

+ `Serif fonts` have a `small stroke` at the `edges` of ***each letter***. They ***create*** a ***sense*** of `formality` and `elegance`.

+ `Sans-serif fonts` have `clean lines` (***no*** `small strokes` ***attached***). They ***create*** a `modern` and `minimalistic look`.

+ `Monospace fonts` have the ***same*** `fixed width`. They ***create*** a `mechanical look`.

+ `Cursive fonts` ***imitate*** `human handwriting`.

+ `Fantasy fonts` are ***decorative/playful*** `fonts`.

</section>

---

<section class="section">
	<h2 class="sentence">The difference between Serif and Sans-serif fonts</h2>

<aside class="notes">
	Note: visit the [CSS Fonts](https://www.w3schools.com/css/css_font.asp) page on w3schools to show the difference between the two font-families and to also show some font examples.
</aside>

</section>
