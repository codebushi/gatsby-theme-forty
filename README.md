# gatsby-theme-forty

Gatsby.js theme based on the Forty site template, designed by HTML5 UP.

## Preview

https://gatsby-theme-forty.netlify.com

## Installation

Install this theme (assuming Gatsby is installed) by running from your CLI:

```shell
gatsby new gatsby-theme-forty https://github.com/codebushi/gatsby-theme-forty
cd gatsby-theme-forty
gatsby develop
```

## Updates

Compared to the original work,

* The Gatsby used by this package has been bumped from 2 to 3.
* The sass version has been bumped to sass 2.
* Drop some deprecated sass usages.
* Drop `javascript:;` deprecated by `React`.

## CSS Grid

The grid on this site was replaced with a custom version, built using CSS Grid. It's a very simple 12 column grid that is disabled on mobile. To start using the grid, wrap the desired items with `grid-wrapper`. Items inside the `grid-wrapper` use the class `col-` followed by a number, which should add up to 12.

Here is an example of using the grid, for a 3 column layout:

```jsx
<div className="grid-wrapper">
    <div className="col-4">
        <p>Content Here</p>
    </div>
    <div className="col-4">
        <p>Content Here</p>
    </div>
    <div className="col-4">
        <p>Content Here</p>
    </div>
</div>
```
