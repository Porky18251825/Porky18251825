- 👋 Hi, I’m @Porky18251825
- 👀 I’m interested in ... learning to write code
- 🌱 I’m currently learning ... Javascript and Python, but I don't know much yet.
- 💞️ I’m looking to collaborate on ... learning how to create useful content to all. 
- 📫 How to reach me ... send me messages in my inbox.
- 😄 Pronouns: ... he/him
- ⚡ Fun fact: ... I'm a truck driver and know nothing about writing code, but I want to learn and I've learned a lot so far, but I need
- to do much better as like I said I don't know very much yet this README.md is the first code I wrote that works the way it is supposed to
- and the end result came out like I wanted. I'm a good learning experience that I don't have much knowledge of yet. Since I wrote this code.
I want to make sure it has the right licenses. so I am applying to this work licensing that I found that I think covers what I'm doing so
I will skip a couple of lines and put the licensing in here just because I'm not sure where to put stuff like that yet better to be safe than
I'm sorry.I applied the Apache 2.0 license and the MIT licenses below this line for the work I did and code I created. I'll do a clock under the last license.
- to prove that I can program and code not good in way, but I can do it. My name is Bobby, by the way, and I'm calling this work or code [shot in the dark]
- because I took a shot in the dark trying to learn this stuff, and I think that I have done well for learning this on my own and shot in the dark is
- my code, no matter how I did it, it's my work, and I grant everyone the same license patents and rights to change and modify all of this code I have to use it
- their own code work. However, they do it they can build off my code just as I did from other software I built on it, and I grant permission to use it free of charge
- and it will always be a work in progress ✨️ sorry I kinda went off here but I didn't know where else to do it now it's time for some clock_label.
- in 24hr I put the clocks above the licensing
- #Import the time module
import time

# Define a function to display the current time in 24hr format
def display_time():
    # Get the current time as a string in the format HH:MM:SS
    current_time = time.strftime("%H:%M:%S")
    # Print the current time with a colon separator
    print(":".join(current_time))

# Call the display_time function every second using a while loop
while True:
    # Clear the previous output
    print("\r", end="")
    # Display the current time
    display_time()
    # Wait for one second
    time.sleep(1) 


    td.today html,
body {
  height: 100%;
}
body {
  font-size: 100%;
  line-height: 1.5;
  font-family: "Roboto Slab", sans-serif;
  background: #f2f2f2;
}
*,
*:before,
*:after {
  box-sizing: border-box;
}
.container {
  max-width: 400px;
  margin: 3em auto 0;
}
.flip-container {
  perspective: 1000;
}
.flip-container:hover .flipper,
.flip-container.hover .flipper {
  transform: rotateY(180deg);
}
.flip-container,
.front,
.back {
  width: 400px;
  height: 400px;
  border-radius: 3px;
}
.flipper {
  transition: 0.5s;
  transform-style: preserve-3d;
  position: relative;
}
.front,
.back {
  -webkit-backface-visibility: hidden;
          backface-visibility: hidden;
  position: absolute;
  top: 0;
  left: 0;
  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.19), 0 6px 6px rgba(0, 0, 0, 0.23);
}
.front {
  z-index: 2;
  transform: rotateY(0deg);
  background: #28283b;
}
.back {
  transform: rotateY(180deg);
  background: #28283b;
}
/*CLOCK*/
.time * {
  text-align: center;
  text-transform: uppercase;
  color: #ffffff;
  font-family: "Roboto Slab", sans-serif;
}
#do-time {
  width: 100%;
  height: 100%;
  position: absolute;
  left: 0;
  right: 0;
  top: 0;
  bottom: 0;
  padding: 1em;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}
.time h2 {
  font-size: 4em;
  font-weight: 400;
  line-height: 1;
}
.time h2 span {
  font-weight: 100;
}
.time h3 {
  font-size: 1.5em;
  font-weight: 100;
  line-height: 1;
  margin-top: 24px;
}
.time h3 span {
  font-weight: 400;
  display: block;
}
.time small {
  font-size: 1em;
  font-weight: 300;
}
/*END CLOCK*/
/*CALENDAR*/
.calendar-wrapper {
  font-family: "Roboto Slab", serif;
  font-weight: 100;
  padding: 2em;
}
tr.days {
  padding-top: 10px;
}
table {
  clear: both;
  width: 100%;
  color: #ffffff;
}
td {
  height: 36px;
  text-align: center;
  vertical-align: middle;
  width: 14.28571429%;
}
td.not-current {
  color: #8c8c8c;
}
td.today {
  color: #ffa500;
  font-size: 1.5em;
}
thead td {
  border: none;
  color: #ffa500;
  text-transform: uppercase;
  font-size: 1.5em;
}
#btnPrev {
  float: left;
  margin-bottom: 20px;
}
#btnPrev:before {
  content: '\f104';
  font-family: FontAwesome;
  padding-right: 4px;
}
#btnNext {
  float: right;
  margin-bottom: 20px;
}
#btnNext:after {
  content: '\f105';
  font-family: FontAwesome;
  padding-left: 4px;
}
#btnPrev,
#btnNext {
  background: transparent;
  border: none;
  outline: none;
  font-size: 1em;
  font-weight: 300;
  font-family: "Roboto Slab", serif;
  color: #8c8c8c;
  cursor: pointer;
  text-transform: uppercase;
  transition: all 0.3s ease;
}
#btnPrev:hover,
#btnNext:hover {
  color: #ffa500;
}
/*END CALENDAR*/ 

https://www.timeanddate.com/worldclock/converter.html?iso=20240303T175100&p1=136&p2=179&p3=5394&p4=248
date.today tk.Tk after 1 second 

# Import the modules
import tkinter as tk
import time
from datetime import date

# Create a window
window = tk.Tk()
window.title("Clock and Calendar")

# Create a label for the clock
clock_label = tk.Label(window, font=("times", 60, "bold"), bg="blue")
clock_label.pack()

# Create a label for the calendar
calendar_label = tk.Label(window, font=("times", 24, "bold"))
calendar_label.pack()

# Define a function to update the clock
def update_clock():
    # Get the current time and format it
    current_time = time.strftime("%H:%M:%S")
    # Update the clock label
    clock_label.config(text=current_time)
    # Call the function again after 1 second
    window.after(1000, update_clock)

# Define a function to update the calendar
def update_calendar():
    # Get the current date and format it
    current_date = date.today().strftime("%B %d, %Y")
    # Update the calendar label
    calendar_label.config(text=current_date)
    # Call the function again after 1 day
    window.after(86400000, update_calendar)

# Call the functions
update_clock()
update_calendar()

# Run the window loop


window.mainloop() http://www.apache.org/licenses/
these were examples that I looked up but I got to play with the codes to all of this and actually 
write working code and have it do what I wanted so I would say that this README.md is probably not what it's supposed to be.
but I don't care I'm just trying to learn it and maybe build something from everything I learned this is where Bobby Ringdahl is singing off for the knight
but one other thing I do not agree to any Warranties in any fashion this software is as is and was not meant for any Particular purpose other than to learn
How to code and write code? So this software can be used by anybody, but you can't hold anything against me in any manner. Because I did this just as a way to learn.
How to do it and what to do and I don't feel that this software was meant for any usable purposes other than learning so buy using it you agree that I have no legal responsibilities or 
Reasons to be prosecuted or sued in any manner. And by using it, you agree not to do that and not come after me in any negative way. This is a notice. This is a notice.
To all involved So these would kind of be my terms and conditions which there are none other than I won't do anything negative to you and you don't do anything negative in any possible theory 
to me all I did was make a fork off the main source code and then came up with my own copyrighted junk code that is only meant for me to use so I can learn how to make good codes 
so I hold no responsibility or Legal obligation or responsibility to anything in this README.md file or for anything that I have made or produced. related to anythings I did 
or was trying to learn about and if anything arises in any manner negative or damaging to me then the whole thing is nullified all code I created.


                                   Apache License
                           Version 2.0, January 2004
                        http://www.apache.org/licenses/

   TERMS AND CONDITIONS FOR USE, REPRODUCTION, AND DISTRIBUTION

   1. Definitions.

      "License" shall mean the terms and conditions for use, reproduction,
      and distribution as defined by Sections 1 through 9 of this document.

      "Licensor" shall mean the copyright owner or entity authorized by
      the copyright owner that is granting the license.

      "Legal Entity" shall mean the union of the acting entity and all
      other entities that control are controlled by, or are under common
      control with that entity. For the purposes of this definition,
      "control" means (i) the power, direct or indirect, to cause the
      direction or management of such entity, whether by contract or
      otherwise, or (ii) ownership of fifty percent (50%) or more of the
      outstanding shares, or (iii) beneficial ownership of such entity.

      "You" (or "Your") shall mean an individual or Legal Entity
      exercising permissions granted by this license.

      "Source" form shall mean the preferred form for making modifications,
      including but not limited to software source code, documentation
      source, and configuration files.

      "Object" form shall mean any form resulting from mechanical
      transformation or translation of a source form, including but
      not limited to compiled object code, generated documentation,
      and conversions to other media types.

      "Work" shall mean the work of authorship, whether in Source or
      Object form, made available under the License, as indicated by a
      copyright notice that is included in or attached to the work
      (an example is provided in the Appendix below).

      "Derivative Works" shall mean any work, whether in Source or Object
      form, that is based on (or derived from) the work and for which the
      editorial revisions, annotations, elaborations, or other modifications
      represent, as a whole, an original work of authorship. For the purposes
      of this license, Derivative Works shall not include works that remain
      separable from, or merely link (or bind by name) to the interfaces of,
      the Work and Derivative Works thereof.

      "Contribution" shall mean any work of authorship, including
      the original version of the work and any modifications or additions
      to that work or derivative works thereof, that is intentionally
      submitted to the licensor for inclusion in the Work legal entity by the copyright owner
      or by an individual or Legal Entity authorized to submit on behalf of
      the copyright owner. For the purposes of this definition, "submitted"
      means any form of electronic, verbal, or written communication sent
      to the Licensor or its representatives, including but not limited to
      communication on electronic mailing lists, source code control systems,
      and issue tracking systems that are managed by, or on behalf of, the
      Licensor for the purpose of discussing and improving the Work, but
      excluding communication that is conspicuously marked or otherwise
      designated in writing by the copyright owner as "Not a Contribution."

      "Contributor" shall mean Licensor and any individual or Legal Entity
      on behalf of whom a Contribution has been received by Licensor and
      subsequently incorporated within the Work.

   2. Grant of Copyright License. Subject to the terms and conditions of
      this License, each Contributor hereby grants to You a perpetual,
      worldwide, non-exclusive, no-charge, royalty-free, irrevocable
      copyright license to reproduce, prepare Derivative Works of,
      publicly display, publicly perform, sublicense, and distribute the
      Work and such Derivative Works in Source or Object form.

   3. Grant of Patent License. Subject to the terms and conditions of
      this License, each Contributor hereby grants to You a perpetual,
      worldwide, non-exclusive, no-charge, royalty-free, irrevocable
      (except as stated in this section) patent license to make, have made,
      use, offer to sell, sell, import, and otherwise transfer the Work,
      where such license applies only to those patent claims licensable
      by such Contributor that are necessarily infringed by their
      Contribution(s) alone or by combination of their Contribution(s)
      with the Work to which such Contribution(s) was submitted. If You
      institute patent litigation against any entity (including a
      cross-claim or counterclaim in a lawsuit) alleging that the Work
      or a Contribution incorporated within the Work constitutes direct
      or contributory patent infringement, then any patent licenses
      granted to You under this License for that Work shall terminate
      as of the date such litigation is filed.

   4. Redistribution. You may reproduce and distribute copies of the
      Work or Derivative Works thereof in any medium, with or without
      modifications, and in Source or Object form, provided that You
      meet the following conditions:

      (a) You must give any other recipients of the Work or
          Derivative Works a copy of this License; and

      (b) You must cause any modified files to carry prominent notices
          stating that You changed the files; and

      (c) You must retain, in the Source form of any Derivative Works
          that You distribute, all copyright, patent, trademark, and
          attribution notices from the Source form of the Work,
          excluding those notices that do not pertain to any part of
          the Derivative Works; and

      (d) If the Work includes a "NOTICE" text file as part of its
          distribution, then any Derivative Works that You distribute must
          include a readable copy of the attribution notices contained
          within such NOTICE file, excluding those notices that do not
          pertain to any part of the Derivative Works, in at least one
          of the following places: within a NOTICE text file distributed
          as part of the Derivative Works; within the Source form or
          documentation, if provided along with the Derivative Works; or,
          within a display generated by the Derivative Works, if and
          wherever such third-party notices normally appear. The contents
          of the NOTICE file are for informational purposes only and
          do not modify the License. You may add Your own attribution
          notices within Derivative Works that You distribute, alongside
          or as an addendum to the NOTICE text from the Work, provided
          that such additional attribution notices cannot be construed
          as modifying the License.

      You may add Your own copyright statement to Your modifications and
      may provide additional or different license terms and conditions
      for use, reproduction, or distribution of Your modifications, or
      for any such Derivative Works as a whole, provided Your use,
      reproduction, and distribution of the Work otherwise complies with
      the conditions stated in this License.

   5. Submission of Contributions. Unless You explicitly state otherwise,
      any Contribution intentionally submitted for inclusion in the Work
      by You to the Licensor shall be under the terms and conditions of
      this License, without any additional terms or conditions.
      Notwithstanding the above, nothing herein shall supersede or modify
      the terms of any separate license agreement you may have executed
      with Licensor regarding such Contributions.

   6. Trademarks. This License does not grant permission to use the trade
      names, trademarks, service marks, or product names of the Licensor,
      except as required for reasonable and customary use in describing the
      origin of the Work and reproducing the content of the NOTICE file.

   7. Disclaimer of Warranty. Unless required by applicable law or
      agreed to in writing, Licensor provides the Work (and each
      Contributor provides its Contributions) on an "AS IS" BASIS,
      WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or
      implied, including, without limitation, any warranties or conditions
      of TITLE, NON-INFRINGEMENT, MERCHANTABILITY, or FITNESS FOR A
      PARTICULAR PURPOSE. You are solely responsible for determining the
      appropriateness of using or redistributing the Work and assume any
      risks associated with Your exercise of permissions under this License.

   8. Limitation of Liability. In no event and under no legal theory,
      whether in tort (including negligence), contract, or otherwise,
      unless required by applicable law (such as deliberate and grossly
      negligent acts) or agreed to in writing, shall any Contributor be
      liable to You for damages, including any direct, indirect, special,
      incidental, or consequential damages of any character arising as a
      result of this License or out of the use or inability to use the
      Work (including but not limited to damages for loss of goodwill,
      work stoppage, computer failure or malfunction, or any and all
      other commercial damages or losses), even if such Contributor
      has been advised of the possibility of such damages.

   9. Accepting Warranty or Additional Liability. While redistributing
      the Work or Derivative Works thereof, You may choose to offer,
      and charge a fee for, acceptance of support, warranty, indemnity,
      or other liability obligations and/or rights consistent with this
      License. However, in accepting such obligations, You may act only
      on Your own behalf and on Your sole responsibility, not on behalf
      of any other Contributor, and only if You agree to indemnify,
      defend, and hold each Contributor harmless for any liability
      incurred by, or claims asserted against, such Contributor by reason
      of your accepting any such warranty or additional liability.

   END OF TERMS AND CONDITIONS

   APPENDIX: How to apply the Apache License to your work.

      To apply the Apache License to your work, attach the following
      boilerplate notice, with the fields enclosed by brackets "[]"
      replaced with your own identifying information. (Don't include
      the brackets!)  The text should be enclosed in the appropriate
      comment syntax for the file format. We also recommend that a
      file or class name and description of purpose be included on the
      same "printed page" as the copyright notice for easier
      identification within third-party archives.

   Copyright [2024] [ Robert Kenneth Ringdahl]

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.


MIT License

Copyright (c) [2024] [Robert Kenneth Ringdahl]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
  

-                
  
<!---
Porky18251825/Porky18251825 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
