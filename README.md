Easy Grid system as the name say, is a easy grid system if you don't want to use a framework with all the functionality, you can use this to make simple responsive websites based on a 12 grid system with a mobile first approach using flexbox for grids.

Created by Robert Kis (https://twitter.com/TheRibi91) with support on http://robertkis.com or e-mail: sayhi@robertkis.com .

To can use you need a compiler for Sass (eg: Compass - http://compass-style.org/ ).

### What's included

Within the download you'll find the following directories and files. You'll see something like this:

```
easy-grid-system/
├── css/
│   ├── styles.css
└── img/               ===== here are two images just for example
├── sass/
│   ├── partials/
│   │           ├── _common.scss
│   │           ├── _media.scss
│   │           ├── _normalize.scss
│   ├── styles.scss
index.html
```
### How to use

Is very easy to use, in index.html is an example.<br/>
Are 5 classes, c-{xs, sm, md, lg, xl}-{1,2,3,4,5,6,7,8,9,10,11,12}.<br/>

xs = extra small devices, < 480px <br/>
sm = small devices, > 480px <br/>
md = medium devices/tablets, > 768px <br/>
lg = large devices, > 992px <br/>
xl = extra large devices/notebooks, > 1200px <br/>

And the numbers represent the columns. <br/>
To align the content inside the lines you can use the class: <br/>
  line-{xs, sm, md, lg, xl}-{top, center, bottom}

  ```
  <div class="line line-md-center">
    <div class="c-xs-10">
      <p>
        This is a paragraph
      </p>
    </div>
    <div class="c-xs-2">
      <p>
        Lorem ipsum dolor sit amet, ex altera putant suavitate pri. Ea mea virtute euismod civibus. Ad ius velit tollit, qui virtute definitiones no. Nam id atqui saepe, nullam petentium efficiantur nec cu. Malis aeterno constituam vix cu.
      </p>
    </div>
  </div>
  ```

Easy example:

```
  <div class="line">
    <div class="c-xs-12 c-md-6">
      <p>
        Lorem ipsum dolor sit amet, ex altera putant suavitate pri. Ea mea virtute euismod civibus. Ad ius velit tollit.
      </p>
    </div>
    <div class="c-xs-12 c-md-6">
      <p>
        Id quis lorem vitae eos. Dolor menandri qui cu. Mea posse verear ad, ius magna referrentur eu, ullum dolorum inimicus ad vel.
      </p>
    </div>
  </div>

```

Everytime you want to use the grid system you will need to wrap your content in a div with a 'line' class.

Nested lines :

```
<div class="line">
  <div class="c-xs-12 c-md-6">
    <p>
      Lorem ipsum dolor sit amet, ex altera putant suavitate pri. Ea mea virtute euismod civibus. Ad ius velit tollit.
    </p>
    <div class="line">
      <div class="c-md-5">
        <p>
          This is another paragraph.
        </p>
      </div>
    </div>
  </div>
</div>

```

## Creator

**Robert Kis**

- <https://twitter.com/TheRibi91>
- <https://github.com/TheRibi>

## Copyright and license

Code and documentation copyright 2016 Robert Kis. Code released under [the MIT license] (https://github.com/TheRibi/Easy-Grid-System/blob/master/LICENSE). Docs released under [Creative Commons](https://github.com/TheRibi/Easy-Grid-System/blob/master/LICENSE).
