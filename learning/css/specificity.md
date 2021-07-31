# CSS Evaluation Order

## Specificity

In CSS, the concept of "specificity" is used when multiple selectors target the same element.

Specificty is a deterministic rule used to evaluate what styling should be picked.

- element selector: 0,0,1
- classes selector: 0,1,0
- id selector: 1,0,0

Meaning: element selectors have the lowest "value" or priority when it comes to overruling its style. Classes selectors have one priority higher, meaning a class selector would overrule an element selector. Lastly, id selectors have the highest priority, meaning they would override any other selector.

**However**, inline styles will beat out element, class, and id selectors.

And the highest prio is using the *!important* tag for a css rule. *!important* rules all.

## Cascade

Specificity is not the only way a browser will determine a rule to apply.

The *order*, or the cascade, of the CSS rules matters as well. Meaning, the CSS rule that is applied **last** in a cascade of style rules will win out over the rules that came before it.
