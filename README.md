# Markdown Document template
This is a template project which I use to render my markdown writen reports
to HTML. Which i can later upload/print to `*.pdf`.

This is not a perfect solution, nor does it want to be :)

## Usage
Markdown to be turned into HTML goes into `src/markdown/` folder. The template and
stylesheets can be freely edited and are located in the `src/resources/ folder`.

To generate `html` run the following command in the root directory

```
./gradlew compileMarkdown
```

The output document will be placed in the `out/gen-html` folder. Here is the sample document rendered

![Sample output](https://cloud.githubusercontent.com/assets/2018617/13298568/f4b9723c-db3f-11e5-84b0-071c39d251a7.png)

#License
Copyright 2016 Nish Tahir

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
