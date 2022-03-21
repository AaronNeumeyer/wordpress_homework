# Project 7 - WordPress Pentesting

Time spent: 5 hours spent in total

> Objective: Find, analyze, recreate, and document **five vulnerabilities** affecting an old version of WordPress

## Pentesting Report

### 1. Multi-File Upload File
  - [ ] Summary: This vulnerability is used by uploading a large file that can be uploaded within the control panael of wordpress 
    - Vulnerability types: XSS
    - Tested in version: 4.2
    - Fixed in version: 4.2.5
  - [ ] GIF Walkthrough: <img src="my_gif_walkthrough_url" width="800">
  - [ ] Steps to recreate: Upload a larger than 2mb file within the multi-file uploader that gives a XSS notification alert.
  - [ ] Affected source code:
    - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php)
### 2. Authenticated Cross Ste Scripting
  - [ ] Summary: This vulnerability shows this webpage incorrectly displaying the edit feature in HTML edit mode. 
    - Vulnerability types: XSS
    - Tested in version: 4.2
    - Fixed in version: 4.3
  - [ ] GIF Walkthrough: <img src="my_gif_walkthrough_url" width="800">
  - [ ] Steps to recreate: 
  - [ ] Affected source code:
    - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php)
### 3. Audio File MP3 Upload XSS
  - [ ] Summary: 
    - Vulnerability types: 4.2
    - Tested in version:
    - Fixed in version: 
  - [ ] GIF Walkthrough: <img src="my_gif_walkthrough_url" width="800">
  - [ ] Steps to recreate: Attempt to upload a MP3 file to the uploader which will results in a XSS notification to appear. 
  - [ ] Affected source code:
    - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php)

## Assets

List any additional assets, such as scripts or files

## Resources

- [WordPress Source Browser](https://core.trac.wordpress.org/browser/)
- [WordPress Developer Reference](https://developer.wordpress.org/reference/)

GIFs created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

Describe any challenges encountered while doing the work

## License

    Copyright [yyyy] [name of copyright owner]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
