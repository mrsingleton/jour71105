# Lists
HTML lets you organize content into list format for legibility and also usability. There are two types of lists -- ordered lists, which are controled by the `<ol>` element; and unordered lists, which are controled by the `<ul>` element.

## Ordered Lists
This list type recognizes each list item as being part of a numbered sequence. It places numbers to the left of each list item beginning with 1, 2, 3 and so on. If you rearrange list items, the numnbering will keep the standard, ordered sequence. This type is best used for listing items that make sense if put into a strict order, such as a ranking.

## Unordered Lists
This list type treats all list items the same and only places bullet dots next to each list item. This type is best used for listing items in an order that isn't necessarily strict.

## Examples

```html
<ol>
  <li>New York City</li>
  <li>Los Angeles</li>
  <li>Chicago</li>
  <li>Houston</li>
  <li>Philadelphia</li>
</ol>
```
which yields:

1. New York City
2. Los Angeles
3. Chicago
4. Houston
5. Philadelphia

```html
<ul>
  <li>Grapes</li>
  <li>Oranges</li>
  <li>Apples</li>
  <li>Peaches</li>
  <li>Pears</li>
</ul>
```
which yields:

- Grapes
- Oranges
- Apples
- Peaches
- Pears

## Challenge
Revisit the navigation menu you created for the Hyperlink lesson's challenge. If you were to give those top level menu items submenu items listed beneath each, how would you use the _attributes_ of ordered lists to create a site map page?
