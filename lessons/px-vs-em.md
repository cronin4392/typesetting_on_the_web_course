
# Comparing Pixels and Ems
## Typesetting on the Web
Stephen Cronin

### Overview</h3>

`px` [pixels] and `em` [ems] are two CSS units available to set type. `rem` [relative ems] are another unit available but we can ignore them for this demonstration.

## Demos

### No difference

In the below example two different lockups are mocked up with `px` and `em` respectively

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

### Recursive scaling


In the below example you can see how the `font-size` set in `em` is having a recursive effect.

    <pre>
&lt;span&gt;Lorem
&lt;span&gt;ipsum
&lt;span&gt;dolor
&lt;span&gt;sit
&lt;span&gt;amet,
&lt;span&gt;consectetur
    &lt;span&gt;adipiscing
        &lt;span&gt;elit.&lt;/span&gt;
    &lt;/span&gt;
&lt;/span&gt;
&lt;/span&gt;
&lt;/span&gt;
&lt;/span&gt;
&lt;/span&gt;
&lt;/span&gt;
    </pre>

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
</div>
</section>
</article>
</main>
