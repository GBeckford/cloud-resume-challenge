## Frontend Technical Specificatin

- Create a static webpage serving an html/javascript resume.

## Resume Formatting

- Quick Bio
- Omit information that cant be used descriminatively (e.g. - Age, race)
- Use [Harvard Resume Template](https://careerservices.fas.harvard.edu/resources/bullet-point-resume-template/)

### Harvard Resume Format Generation
Will attempt to use AI to generate initial html/Css and reformat/refactor after.


'''text
Prompt to Gemini: Convert this resume format into html without using a css framework
Please use minimal CSS tags
'''

Image provided:
![Harvard Resume Format](./Docs/Harvard%20REsume%20format.jpg)

This is the output:
[Initial output](./Docs/2025-11-26%20Resume.html)

## HTML amendments
- UTF8 supports most languages
- Mobile support planned so width=device-width viewport metatag has been kept
- CSS will be in separate stylesheet after HTML is adequate
- HTML/CSS selectors will be minimised
- For HTML page two space soft tabs will be used