#btns

Use one background color to generate a large set of pre-configured, Sass based CSS buttons.

##Usage

- Go to where the CSS sits within your project folder:

	`cd your/project/css/directory`

- Clone this repository into your CSS directory (note the `.` at the end):

	`git clone https://github.com/FD0000/btns.git .`

- Start watching `btns.scss`:

	`sass --watch sass/btns.scss:btns.css --style expanded`

- Open `btns.scss` and modify the base-bg color declaration at the top:

	`$btn-base-bg: #FD0000;`

- If needed - open `btns.html` in a browser to test how the button styles look.

##Notes

- Requires [Sass](http://sass-lang.com/).
- See the [Wiki](https://github.com/FD0000/btns/wiki/Project-Goals) for the Project Roadmap.
