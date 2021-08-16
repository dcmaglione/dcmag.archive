# dcmag.archive
Website created for the sole purpose of detailing my experiences, projects, tech stack, etc. Additionally, this site doubles as a Gemini Capsule.

## Description
This site uses a new Internet protocol called Gemini which can be seen as a middle ground between the old gopher protocol of the early 1990s and the modern web. Gemini attempts to address the weaknesses of gopher while avoiding the pitfalls of the web.

Gemini is written in a markdown-like syntax. Links can only be written and displayed one per line, similar to gopher. Additionally, there are no images, videos, and advertisements.

## Installation
The website is written in raw HTML, CSS, and gemtext, so no additional installations are required.

## Usage
Assuming the repository has been cloned to the desired directory to view the website locally, using HTTP, run the following inside the project directory:

```terminal
python -m http.server
```

By default the local server will run on port 8000. If you wish to change this simply add the port number (for example):

```terminal
python -m http.server 5000
```

The above will direct the local server to run on port 5000.

Please note, if you are using Python 2 (instead of Python 3) the equivalent command is:

```terminal
python -m SimpleHTTPServer
```

## Contributing
These source files are not open to contributions as I use this website to detail various aspects of my professional life.

## Acknowledgment
The inspiration to create a Gemini Capsule came from Derek Taylor, also known as [distro.tube](https://distrotube.com/).

## License
[MIT](https://choosealicense.com/licenses/mit/)
