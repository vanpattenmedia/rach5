# Rach5

### What is Rach5?
**Rach5** (that's pronounced _Rock_ as in _Rach_-maninov) is a WordPress theme boilerplate developed by Chris Van Patten for Van Patten Media.

Rach5 provides a set of "sensible defaults" that make it faster to jump into developing a custom WordPress website, and get right out of your way as quickly as possible by not imposing any (well, almost any) style decisions. Rach5 uses HTML5, Ruby and Compass, and a mix of WordPress native and custom functions that make theme development fast and fun.

### 1.0
Rach5 has finally hit 1.0! What does that mean for you?

*   All the functions have been removed. They will now be maintained in a separate project: `rach5-plugin`.
*   The project has been condensed to only include the theme directory to simplify management via version control. The plugin will be built to handle maintenance and offer humans.txt/robots.txt defaults.
*   In the interest of maintainability and simplicity, I have removed several template files and condensed them down to loop templates that are called from conditionals in `index.php`. This logic is not typical for WordPress, but is a major part of bringing <a href="https://en.wikipedia.org/wiki/DRY">DRY</a> to Rach5.

For up-to-date documentation, visit the Rach5 website at <a href="http://www.vanpattenmedia.com/projects/rach5/">Van Patten Media Labs</a> or the <a href="https://github.com/vanpattenmedia/rach5/wiki">Github Wiki</a> for the project.

### Getting started
It's easy to <a href="https://github.com/vanpattenmedia/rach5/wiki/Getting-Started">get started with Rach5</a>! The full details are available at the wiki.

### Todo List/What's Done
See the wiki for the <a href="https://github.com/vanpattenmedia/rach5/wiki/Todo-List">todo list</a> and list of <a href="https://github.com/vanpattenmedia/rach5/wiki/What's-Done">completed items</a>.

### License
**Copyright (C) 2011-2013, Chris Van Patten.**
All rights reserved.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

*   Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.
*   Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.
*   Neither the name of the organization nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
