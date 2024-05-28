# CSV 2024 - CFIA NCFAD Genomics Unit poster

A scientific conference poster to be presented at the 5th Symposium of the Canadian Society for Virology ([CSV2024](https://harlowagency.swoogo.com/CSV)) going over the Canadian Food Inspection Agency (CFIA) National Centre for Foreign Animal Disease (NCFAD) Genomics Unit led by Dr Oliver Lung.

## Building from source

A full TexLive install is probably recommended. Compilation has only been tested on Linux with LuaLaTeX.

Compile `poster.tex` with [LuaLaTeX](https://www.luatex.org/) to PDF:

```bash
git clone https://github.com/CFIA-NCFAD/2024-CSV-lab-overview-poster
cd 2024-CSV-lab-overview-poster
latexmk -lualatex poster.tex
# skip errors/warnings; press Enter
```

Or use the excellent [SublimeText/LaTeXTools](https://github.com/SublimeText/LaTeXTools/) plugin for the Sublime Text editor.

## Legal

Copyright 2024 Government of Canada

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this work except in compliance with the License. You may obtain a copy of the License at:

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
