# CSS Grid

## 🔍 Research & Learning 
![img](/img/css-box-model.png)

### What is `1rem`?
+ Most browsers set the root font size to `16px` (by default) so `1rem == 16px`
+ Example:
    + `2rem == 2 * 16px` which become `2rem == 32px`

### What is `fr`?
> **Note: `fr`(fraction) a unit of length 

`fr` **behave relative** to the **`grid-container`** not to the window
```css
    grid-template-columns: 1fr 1fr 1fr;    /* cover the whole screen*/

    /* Relative to the grid-container */
    grid-template-rows: 1fr 1fr 1fr;       /* does not cover the whole screen*/
```
> If you want, you can manually adjust the height of `grid-container`

