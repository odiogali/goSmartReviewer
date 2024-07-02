# Smart Review (Written in Go)
Smart Review is a project that seeks to automate the process of deciding what to review. It deals with:
- Deciding what note to review based on what you've reviewed in the current cycle
- Formatting the notes such that they can be viewed as they are in your markdown editor
- Sending the note as a formatted email so you get reminded to review and know what to review
- A mechanism for testing yourself on the material you just reviewed

# How to Use It
1. Run this command in your terminal `git clone https://github.com/MisterBra1n/goSmartReview.git`
2. Start by specifying the three subjects you would like to review by replacing the paths to their directories
3. Specify the email you want the message to be sent from and the password denoted by 'mailPass'
4. Specify the email you want the message to be received at
5. You may also change the frequency you receive the review notes depending on how you use it
6. Find a machine you can run the code in perpetuity on / AWS or some other cloud computing service
