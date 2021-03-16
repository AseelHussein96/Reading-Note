# What Google Learned From Its Quest to Build the Perfect Team 
Psychological safety: Everyone feels safe in taking risks around their team members, and that they won't be embarrassed or punished for doing so. Dependability: Everyone completes quality work on time. Structure and clarity: Everyone knows what their specific expectations are.
### The key characteristics of Improved teams
After years of analyzing data and interviews from more than 180 teams across the company, Google found that the kinds of peopl in a team no so pertinent.
Instead, the researchers found that there were five key characteristics of improved teams:
1- Psychological safety: Everyone feels safe in taking risks around their team members, and that they won’t be embarrassed or punished for doing so.
2- Dependability: Everyone completes quality work on time.
3- Structure and clarity: Everyone knows what their specific expectations are. These expectations must be challenging yet attainable.
4- Meaning: Everyone has a sense of purpose in their work (i.e., financial security, supporting family, helping the team succeed, etc.).
5- Impact: Everyone sees that the result of their work actually contributes to the organization’s overall goals.
### Not all researchers agree
While Google’s findings may be true to some extent, a large number of scientific studies have caused researchers (outside of Google’s lab) to shockingly disagree. They claim the exact opposite — that personality, not just skills, is indeed a significant factor in what makes a team successful.

![google image](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSIbmIOBtvOB-2frH9dM72TFU8HscyEcHP81A&usqp=CAU)

# css (transforms) 
CSS transforms are a collection of functions that allow to shape elements in particular ways: translate: moves the element along up to 3 axis (x,y and z) rotate: moves the element around a central point. scale: resizes the element.

### Values
- scale(): Affects the size of the element. This also applies to the font-size, padding, height, and width of an element, too. It’s also a a shorthand function for the scaleX and scaleY functions.
- skewX() and skewY(): Tilts an element to the left or right, like turning a rectangle into a parallelogram. skew() is a shorthand that combines skewX() and skewY by accepting both values.
- translate(): Moves an element sideways or up and down.
- rotate(): Rotates the element clockwise from its current position.
- matrix(): A function that is probably not intended to be written by hand, but combines all transforms into one.
- perspective(): Doesn’t affect the element itself, but affects the transforms of descendent elements’ 3D transforms, allowing them all to have a consistent depth perspective.

### skw: 
The skew() element performs a shear transformation (also known as a shear mapping or a transvection), which displaces each point of an element by a given angle in each direction.

Skewing an element is kind of like taking the points of an element, and pushing or pulling them in different directions, based on a given angle.
example :
```
{
  skew(ax)

skew(ax, ay)
}
```
### rotate: 
This rotates an element clockwise from its original position, whilst a negative value would rotate it in the opposite direction. Here’s a simple animated example where a square continues to rotate 360 degrees every three seconds
```
h1
{
rotation-point:50% 50%;
rotation:180deg;
}
```
### transforms;
Probably the most useful of the transformations, rotate does exactly what it says on the tin: it rotates any element. The browser should not assume the unit of measurement used, so it needs to be included for the rotation: radians (rad), turns (turn) or degrees (deg) for degrees. To provide one example, sans vendor prefixes:
```
img#inception {
	width: 400px;
	height: 267px;
	border: 15px solid #ffd;
	transform: rotate(2.5deg);
	float: left;
	margin-right: 2em;
}
```
The major issue that non-IE browsers have is one of smoothing and antialiasing edges of rotated elements, especially text, although this has taken dramatic steps forward in recent browser versions.

# Transition and Animation 
- transition 
The simplest (and most straightforward) way to animate your components is through CSS Transitions. In this article, you’ll learn how CSS Transitions work, and how to make animations with it.

A transition occurs when a CSS property changes from one value to another value over a period of time.
transition-property refers to the CSS property you wish to transition. It is required in the transition shorthand.

transition-duration refers to the duration of the transition. How long do you want the transition to last? This value is written in seconds with the s suffix (like 3s). It is also required in the transition shorthand.

transition-timing-function refers to how to transition occurs. You’ll learn more about this later.

transition-delay refers to how long you want to wait before starting the duration. This value is written in seconds with the s suffix (like 3s). transition-delay is optional in the transition shorthand.

![css ](data:image/jpeg;base64,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)

-Animation 
By now you’ve probably heard at least something about animation in CSS3 using keyframe-based syntax. The CSS3 animations module in the specification has been around for a couple of years now, and it has the potential to become a big part of Web design. Using CSS3 keyframe animations, developers can create smooth, maintainable animations that perform relatively well and that don’t require reams of scripting. It’s just another way that CSS3 is helping to solve a real-world problem in an elegant manner. If you haven’t yet started learning the syntax for CSS3 animations, here’s your chance to prepare for when this part of the CSS3 spec moves past the working draft. In this article, we’ll cover all the important parts of the syntax, and we’ll fill you in on browser support so that you’ll know when to start using it.

![css ](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_124b8aca585c9626cb20541ec655726c.png)

# 8 SIMPLE CSS HOVER EFFECTS
ith support for CSS3 increasing with each new release for every browser, and those tiresome CSS2-only browsers slowly dropping off the usage charts, we have far more options for hover effects and transitions in general. Almost all the calls to action that you see on the Web use some form of hover effect, because they draw the eye and make a website feel more engaging
1. HORIZONTAL IMMERSION 
A style I’ve been seeing more and more of lately is one where a semi-transparent background color makes the button appear to be immersed on hover. It usually comes from one side and transitions until the entire button is covered.
2. VERTICAL IMMERSION
This effect is very similar to the one above, except that in this case we’ll be animating the height to make the color seem like it’s falling from the top of the button
3. GHOST BUTTON
In this little snippet we’ll add a simple but highly effective transition to the button. The ghost button effect is when we invert the color in the button and add a border
4. ICON ANIMATE IN
This effect is great for functions, like adding an item to a cart, or submitting a form. What we’ll do is have an icon slide in and appear next to the text, when the user hovers over the button.
5. BOUNCE EFFECT
In this animation we’re going to set some keyframes for the button so that we have a bounce effect when the user hovers on it. This is always a great way to grab a user’s attention.
6. SKEW
Skew is definitely one of the most peculiar transforms in CSS3. We’ve had it in Photoshop for years, but getting in in CSS3 was a surprise to say the least
7. DOTTED BORDER
This effect is a lot like the ghost button effect, but instead of a uniform border, we get a dotted line
8. FLIP 3D EFFECT
This last effect is a little more complicated since it involves flipping the button over to reveal another message we’ve added in the after pseudo-element of the button.
