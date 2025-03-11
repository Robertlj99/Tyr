
### Mobile First Development

All beginning parameters are designed first to fit my iPhone. I am only listing parameters that are affected by media queries.

### Beginning Parameters

- **Body
	- font-size: 20px;
- **Nav-wrapper
	- bottom: 0;
- **Gradient Bar
	- height 1.5vh;
	- bottom: 0;
- **Navbar
	- grid-template-columns: 1fr 1fr 1fr;
	- height 8vh;
	- padding-bottom: 1vh;
- **Navbar h1
	- font-size 35px;
- **Icon Container span
	- font-size 14px;
- **Card Container
	- margin: 0;

## Changes by Query Size

### Small (640px)

None so far

### Medium (768px, iPad)

Increase font sizes,

- **Body
	- font-size 22px;
- **Navbar
	- height: 7vh;
- **Navbar h1
	- font-size: 40px;
- **Icon Container Span
	- font-size 16px;

### Large (1024px, iPad horizontal)

Move the nav-wrapper and its components to the top of the page and adjust the necessary paddings. Add margin for the card containers now that navbar is stuck to the top of the page. Adjust navbar grid layout to better space icons around logo

- **Nav-wrapper
	- bottom: unset;
	- top: 0;
- **Gradient-bar
	- bottom: unset;
	- top: 0;
- **Navbar
	- padding-top: 1vh;
	- padding-bottom: 0vh;
	- grid-template-columns: 1fr 2fr 1fr;
- **Card container
	- margin-top: 9vh;

### XL (1200px, Laptop)

Adjust navbar size, grid layout, and the necessary margins from the changes

- **Navbar
	- height: 9vh;
	- grid-template-columns: 1fr 4fr 1fr;
- **Card container
	- margin-top: 10vh;

### 2XL (1536px, desktop)

Big boys, adjust sizing for my monitor

- **Body
	- font-size: 26px;
- **Gradient bar
	- height: 0.5vh;
- **Navbar
	- height: 4.5vh;
	- grid-template-columns: 1fr 6fr 1fr;
- **Navbar h1
	- font-size: 45px;
- **Icon container span
	- font-size: 20px;
- **Card container
	- margin-top: 5.5vh;

