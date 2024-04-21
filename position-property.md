# Display Property
- Static
- Relative
- Fixed
- Absolute
- Sticky

# Observations 
### Static:
  - This is default position
  - No alignments can takeplace {left right, top, bottom}

### Relative:
  - Alignment can takeplace {left, right, top, bottom}
  - Alignment starts after default margin
  - It is positioned relative to its normal position

### Fixed:
  - Alignment can takeplace {left, right, top, bottom}
  - Alignment starts from 0px { margin:0px }
  - It always fix in the same place, even if the page is scrolled
  - Width / height depends on the content

### Absolute
  - Positioned relative to the nearest positioned ancestor
  - If it has no positioned ancestors, it uses the document body, and moves along with page scrolling
  - Elements are removed from the normal flow, and can overlap elements

### Sticky
  - It is positioned based on the user's scroll position
  - It is positioned relative until a given offset position is met in the screen, then it sticks in place ( like position: fixed; )