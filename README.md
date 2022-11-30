# me.crump.space - A professional resume for Tyler Crumpton

_Instructions here are mostly intended for future-Tyler so that he remembers how to update and run this thing_

## Running locally with Docker

To test locally with docker, run the following in your terminal after installing docker into your system:

1. `docker run -p 4000:4000 -v $(pwd):/site bretfisher/jekyll-serve`
2. Navigate to `http://localhost:4000`

### Customizing

#### Options/configuration

Most of the basic customization will take place in the `/_config.yml` file. Some special ones to note:

- `resume_header_contact_info`: Use this to set your address and phone number (but don't commit this!)
- `display_header_contact_info`: Set this to `true` to display the above information (just for making paper or PDF copies, don't publish this to the Internet)

#### Editing content

Most of the content configuration will take place in the `/_layouts/resume.html` file, so edit the markup there accordingly.

## License

The code and styles are licensed under the MIT license. [See project license.](LICENSE) Obviously you should not use the content of this repo in your own resume. Also, you should totally check out the parent repo [jglovier/resume-template](https://github.com/jglovier/resume-template) instead! :wink:
