# CSS BOX MODEL
## What is a CSS Box Model
The CSS box model  applies to block boxes and defines how the different parts of a box - ```margin```, ```border```,```padding```, and ```content``` - work together to create a box that you can see on a page. Inline boxes use just some of the behavior defined in the box model.

## What are the parts of a box
- **margin** - Clears an area outside the border. The margin is transparent.
- **border** - A border that goes around the padding and content.
- **padding** - Clears an area around the content. The padding is transparent.
- **content** - The content of the box, where text and images appear.

A clear view of the box model  
![Box Model Picture](https://github.com/Manifest-Son/CSS-Box-Model/blob/first_commit/assets/box-model.png)  
## Further explanation of the box parts
### Margin
The margin is an invisible space around your box. It pushes other elements away from the box.  
We can control all margins of an element at once using the margin property, or each side individually using the equivalent longhand properties:
- ```margin-top```
- ```margin-bottom```
- ```margin-left```
- ```margin-right```

### Padding
The padding sits between the border and the content area and is used to push the content away from the border.
The padding property controls the padding on all sides of an element. To control each side individually, use these longhand properties:
- ```padding-top```
- ```padding-bottom```
- ```padding-right```
- ```padding-left```

### Border
The border is drawn between the margin and the padding of a box. If you are using the standard box model, the size of the border is added to the width and height of the content box.  
You can set the width, style, or color of all four borders at once using the border property.
To set the properties of each side individually, use:
- ```border-right```
- ```border-left```
- ```border-top```
- ```border-bottom```

## Box model in action💡
We have a heading in our HTML file that we need it to have a curved border and text placed in a box.
```html
<h1>Welcome to my Blog</h1>
```
Here is its CSS
```css
h1{
    border: 2px solid red;
    margin: 50px 80px 50px 80px;
    padding: 20px 30px 30px 20px;
    border-radius: 10px;
}
```

The four values in both margin and padding follow in this order:  
_top_ _right_ _bottom_ _left_.  

Here is the output.  
![CSS applied on a heading](https://github.com/Manifest-Son/CSS-Box-Model/blob/first_commit/assets/heading.png)

Congratulations!! Having gone through this README.md file and certain that you understand the Box Model.
