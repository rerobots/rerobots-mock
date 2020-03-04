Introduction
============

Summary
-------

This server mocks the rerobots API, using an internal finite-state machine to
simulate actions like requesting an instance, applying an add-on, etc. There are
parameters to configure the initial state and time behavior.


Building and testing
--------------------

A [Git LFS](https://git-lfs.github.com/) client is required to clone this
repository. Note that `git clone` will succeed without `git lfs` available, but
some large files will not be fetched.


Testing
-------

`pylint rmock`


Participating
-------------

All participation must follow our code of conduct, elaborated in the file
CODE_OF_CONDUCT.md in the same directory as this README.

Reporting errors, requesting features
`````````````````````````````````````

Please first check for prior reports that are similar or related in the issue
tracker at https://github.com/rerobots/rerobots-mock/issues
If your observations are indeed new, please `open a new
issue <https://github.com/rerobots/rerobots-mock/issues/new>`_

Reports of security flaws are given the highest priority and should be sent to
<security@rerobots.net>, optionally encrypted with the public key available at
https://rerobots.net/contact Please do so before opening a public issue to allow
us an opportunity to find a fix.

Contributing changes or new code
````````````````````````````````

Contributions are welcome! There is no formal declaration of code style. Just
try to follow the style and structure currently in the repository.

Contributors, who are not rerobots employees, must agree to the `Developer
Certificate of Origin <https://developercertificate.org/>`_. Your agreement is
indicated explicitly in commits by adding a Signed-off-by line with your real
name. (This can be done automatically using ``git commit --signoff``.)


License
-------

This is free software, released under the Apache License, Version 2.0.
You may obtain a copy of the License at https://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
