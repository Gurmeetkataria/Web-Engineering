# CSS - (Day-08) - Revision Notes

---

## 1. Alpha & Opacity

**Opacity** in CSS controls the transparency of an element. The value ranges from `0` (completely invisible) to `1` (fully visible). It can be used to fade elements in/out or give layered effects.

You can also use `rgba()` to control the transparency of background colors.

```css
.box {
  opacity: 0.5; /* Element is 50% transparent */
  background-color: rgba(255, 0, 0, 0.3); /* Red with 30% opacity */
}

2. Transitions in CSS
Transitions allow CSS property changes to occur smoothly over a set duration instead of instantly. This helps create animations like hover effects, color fades, or movement.

css
Copy
Edit
.box {
  transition: all 0.4s ease;
}
.box:hover {
  background-color: blue;
  transform: scale(1.1);
}
3. Transform - Rotate
Rotate is used to turn an element clockwise or counterclockwise by a certain angle.

css
Copy
Edit
.box {
  transform: rotate(45deg); /* Rotates the element 45 degrees */
}
Useful for creating animated icons, rotated text, or dynamic layouts.

4. Transform - Scale
Scale increases or decreases the size of an element. It doesn’t affect the actual layout, just the visual appearance.

css
Copy
Edit
.box {
  transform: scale(1.2); /* 120% of original size */
}
Great for hover zoom effects on buttons or images.

5. Transform - Translate
Translate moves an element from its original position along the X and Y axes.

css
Copy
Edit
.box {
  transform: translate(50px, 20px); /* Right 50px, down 20px */
}
Used to create smooth motion or offset effects.

6. Transform - Skew
Skew tilts an element along the X and/or Y axis, creating a slanted look.

css
Copy
Edit
.box {
  transform: skew(20deg, 10deg);
}
This is mostly used for creative or stylized layouts.

7. Box Shadow
Box-shadow adds a shadow effect around an element’s box, helping to create depth or elevation.

css
Copy
Edit
.box {
  box-shadow: 4px 4px 12px rgba(0, 0, 0, 0.3);
}
You can control horizontal offset, vertical offset, blur, and color.

8. Background Image
Background-image is used to apply an image behind an element’s content.

css
Copy
Edit
.box {
  background-image: url("image.jpg");
  background-size: cover;
  background-position: center;
}
This is commonly used for hero sections, cards, or full-page banners.

9. Card Hover Effect
Card hover effects use a mix of transition, transform, or box-shadow to add interactivity to cards when the user hovers over them.

css
Copy
Edit
.card {
  transition: all 0.3s ease;
}
.card:hover {
  transform: scale(1.05);
  box-shadow: 0 8px 20px rgba(0, 0, 0, 0.2);
}
Great for making UI/UX more interactive and attractive.

10. Position Property
Position in CSS defines how an element is placed in the document layout.

static: Default, follows the normal document flow.

relative: Positioned relative to its normal position.

absolute: Positioned relative to the nearest positioned ancestor.

fixed: Stays in place even when scrolling.

sticky: Acts relative until it reaches a defined scroll position.

css
Copy
Edit
.box {
  position: absolute;
  top: 20px;
  left: 50px;
}
Used for menus, tooltips, layouts, and sticky headers.

11. Simple Smiley Face (Using CSS)
A smiley face can be created using HTML & CSS by using border-radius, position, and custom shapes.

html
Copy
Edit
<div class="face">
  <div class="eye left"></div>
  <div class="eye right"></div>
  <div class="smile"></div>
</div>
css
Copy
Edit
.face {
  width: 120px;
  height: 120px;
  background: yellow;
  border-radius: 50%;
  position: relative;
}

.eye {
  width: 10px;
  height: 10px;
  background: black;
  border-radius: 50%;
  position: absolute;
  top: 30px;
}

.left {
  left: 30px;
}

.right {
  right: 30px;
}

.smile {
  width: 60px;
  height: 30px;
  border-bottom: 5px solid black;
  border-radius: 0 0 50% 50%;
  position: absolute;
  bottom: 30px;
  left: 30px;
}
Fun way to learn positioning, background colors, and border-radius.