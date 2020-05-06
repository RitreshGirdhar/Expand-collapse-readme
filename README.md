# Expand-collapse-readme

Sometime we need to add expand/collapse section in our README file. I created this repo to quickly check README changes.


# A collapsible section containing markdown
<details>
  <summary>Click to expand!</summary>
  
  ## Heading
  1. Heading 1
  2. Heading 2
     * With some
     * Sub bullets
</details>

# A collapsible section containing code
<details>
  <summary>Click to expand!</summary>
  
  ```javascript
    function whatIsLove() {
      console.log('Baby Don't hurt me. Don't hurt me');
      return 'No more';
    }
  ```
</details>

# How to structure
```
# A collapsible section with markdown
<details>
  <summary>Click to expand!</summary>
  
  ## Heading
  1. A numbered
  2. list
     * With some
     * Sub bullets
</details>
```
**NB:** Make sure you have an **empty line** after the closing `</summary>` tag, otherwise the markdown/code blocks won't show correctly.

**NB**: Make sure you have an **empty line** after the closing `</details>` tag if you have multiple collapsible sections.
