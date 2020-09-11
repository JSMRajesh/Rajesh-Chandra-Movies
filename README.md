

### Stage 1

Take this opportunity to inspect the code, run the project and try to debug and fix the issues you find in this existing project built with React Native.
During your interview you will need to answer questions about how you found the bugs you found, what the reasons behind your specific fixes are, and why you decided some particular working code needed improvement.

### Goal
1. Be able to run the project
2. Identify and fix bugs
3. Improve performance when possible
4. Do **not** spend more than 2 hours

#### Instructions
1. Clone this repository. (**do not fork it**)
2. With your own GitHub account, create a public repository containing the code you cloned in step 1 and name it \<firstname-lastname-movies\>.
3. Notify the interviewer by sending them a link to your repository.
4. Start your debugging session and fix everything you are able to find.
5. Commit the changes to **your** repository.
6. Prepare for the interview and have your camera on ;).

#### Pro tip
* You'll notice the animated transitions in the app are not very smooth. The animation itself is *not* the problem.



#### ISSUES Found
1. Pod file was incorrect, Removed TVOS to make it work
2. Images are too large, we need to resize image to make it fit
3. Scroll is lazy. Not smooth
4. Replaced Scrollview with FlatList for performane improvement and smooth scolling
5. Loading Movielength in method rather then sending param through **generateMovies()**

