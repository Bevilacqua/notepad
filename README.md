# notepad
A CSS library for simple floating notes.

## Philosophy
_Let elements on a page float independently from each other upon an upstream river._

## Design Principles
Each notepad should flow from bottom to top and contain a collection of notes or note-columns.

+ __Note__  
  A note is a rectangular div aligned with flexbox that seems to float above it's parent element.
  The basic floating is achieved via a box shadow with default:
  ```
  -webkit-box-shadow: 0px 5px 5px 0px rgba(0, 0, 0, 0.5);
  -moz-box-shadow:    0px 5px 5px 0px rgba(0, 0, 0, 0.5);
  box-shadow:         0px 5px 5px 0px rgba(0, 0, 0, 0.5);
  ```

+ __Note-Column__  
  A note column can be seen as a smaller notepad within a larger notepad. Columns lined up side by side allow for two or more streams of notes



