# Mon Projet

This is a basic project setup with a 7-1 SCSS architecture and an index.html file.

## Project Structure

The project has the following structure:

```
mon-projet
├── scss
│   ├── abstracts
│   │   ├── _variables.scss
│   │   └── _functions.scss
│   ├── base
│   │   ├── _reset.scss
│   │   └── _typography.scss
│   ├── components
│   │   └── _buttons.scss
│   ├── layout
│   │   ├── _header.scss
│   │   └── _footer.scss
│   ├── pages
│   │   └── _home.scss
│   ├── themes
│   │   └── _theme.scss
│   ├── vendors
│   │   └── _bootstrap.scss
│   └── main.scss
├── css
│   └── style.css
├── index.html
└── README.md
```

## Installation

To install this project, you need to have Node.js and npm installed on your machine. Then, follow these steps:

1. Clone the repository: `git clone https://github.com/username/mon-projet.git`
2. Navigate to the project folder: `cd mon-projet`
3. Install the dependencies: `npm install`
4. Start the project: `npm start`

## Usage

After starting the project, open `index.html` in your browser to view the website.

To make changes to the styles, modify the SCSS files in the `scss` folder. The changes will be automatically compiled to `css/style.css`.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)