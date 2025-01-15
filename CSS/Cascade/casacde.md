# The cascade of CSS

Sometimes the css doesn't provide correct outcomes (Unexpected behavior), It may be of following causes:

- Default style

- Cascade

---

The cascade is what determines which rules actually get applied to our HTML.

- Specificity <br>
A CSS declaration that is more specific will take precedence over less specific ones. <br>
Note: Inline styles has the highest priority.<BR>
The more specific the selector, the more priority it gets.<br>
The selectors listed according to the specificity:<br>

1. ID selector
2. Class selector
3. Type selector
4. other selector<br>
In case of having same specificity, the higher number of specificity beats the lower.<br>
Note: When comparing selectors, you may come across special symbols for the universal selector (*) as well as combinators (+, ~, >, and an empty space). These symbols do not add any specificity in and of themselves.<br>

---

- Inheritance<br>
The css properties of the element are inherited by the descendant even if we don't explicitly define so.<br>
The exception to this is if we specifically target the child element.

---

- Rule order <BR>
The final factor, the end of the line, the tie-breaker of the tie-breakers. <BR>
The last rule gets applied if everything else is tested to be equal.