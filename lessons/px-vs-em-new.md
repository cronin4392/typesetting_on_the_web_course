# Comparing Pixels and Ems
## Typesetting on the Web
By Stephen Cronin

### Overview

`px` [pixels] and `em` [ems] are two CSS units available to set type. `rem` [relative ems] are another unit available but we can ignore them for this demonstration.

## Demos

### No difference

In the below example two different lockups are mocked up with `px` and `em` respectively however their visual output is the same.

#### Demo

@EMBED no-difference-pixels

@EMBED no-difference-ems

#### Code

```html
<div class="demo demo-recursive-em">
    <span>Lorem
        <span>ipsum
            <span>dolor
                <span>sit
                    <span>amet,
                        <span>consectetur
                            <span>adipiscing
                                <span>elit.</span>
                            </span>
                        </span>
                    </span>
                </span>
            </span>
        </span>
    </span>
</div>
```

#### Demonstration

By changing the `font-size` on the parent element we can see all of our other type scale proportionally. A `px` typeset layout does not have this ability.

@EMBED no-difference-ems

### [Trick] Recursive scaling

In the below example you can see how the `font-size` set in `em` is having a recursive effect.

#### Demo

@EMBED recursive-scaling

#### Code

```html
<div class="demo demo-recursive-em">
    <span>Lorem
        <span>ipsum
            <span>dolor
                <span>sit
                    <span>amet,
                        <span>consectetur
                            <span>adipiscing
                                <span>elit.</span>
                            </span>
                        </span>
                    </span>
                </span>
            </span>
        </span>
    </span>
</div>
```

