## Drum Kit

### Key Learnings

**<audio>**

- Audio element is not displayed if controls attribute is not specified.
- We can have multiple audio sources in a single element, as a fallback option.

```
<kbd>
```

- Represents keyboard element.

```
<blockquote>
```

- Indicates a section quoted from other source.

**Data Attributes**

- Hey! You just can't keep adding your own attributes to html elements. It's not considered good practice. Use 'data-\*' attributes instead.

**Transition End Event**

- 'transitionend': Hey! You just can't remove transition class using key.classList.remove('className'). Use 'transitionend' event instead.

### Alternate Implementations

- const keys = document.querySelectorAll('.key');
  keys.forEach((key) => key.addEventListener('transitionend', removeClass));

- const keys = document.querySelector('.keys');
  keys.addEventListener('transitionend', removeClass);

### References

- Audio Element: @ https://developer.mozilla.org/en-US/docs/Web/HTML/Element/audio
- Audio/Video Methods: @ https://www.w3schools.com/tags/ref_av_dom.asp
- kbd Element: @ https://developer.mozilla.org/en-US/docs/Web/HTML/Element/kbd#echoed_input
