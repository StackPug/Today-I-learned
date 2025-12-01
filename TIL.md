Today I learned

Thursday 27th November 2025

Today I learned more about what happened last night when I tried to add an about me to my website. I have learnt the HTML basics from Free Code Camp on what to add to the website and how to add a nav (navigation) bar. I added one for the about me section. Eventually I will make it so it opens a new page, but I got lost in the GITHub hole and really enjoyed how it kept breaking. I learnt that it wouldn't push it because of the changes made and it opened VIM which I had no idea how to get out of. Since learned ESC, :wq means save and quit. I also learned that git commit -m "ENTER MESSAGE HERE" is how I can name my file/commit without it opening VIM and confusing me. 
I am currently making a new repo called "Today I learned" and think this is a cool way for me to jot down what I have learned everyday and keep a diary. I have tried doing this the old fashioned way with paper and pen but I love this idea of keeping it digital and it will also count to me being active on GITHub. 
So in doing this I have learnt that mkdir means make directory and then you put the name you would like it to be. I have learned that TOUCH and a name you put here, opens a new notes file but if it is a name that is already taken it will open and update that version. 
git init - initialised git repo
git add TIL.md - added the file
git commit -m "Add first TIL notes" - saved as 
I carried on and learnt how to make folders but then decided I didn't need lots of folders and one notes file is enough so I learned how to delete them. 
rm r (foldername) deletes a folder and files in it
rm (filename) deletes a file

Friday 28th Novemeber 2025 

Today I started with updating my website. I added a footer element, made a new, seperate page for my about-me to open up when you click on it and changed the style of the nav bar. I did the footer and the about me page myself but, I had to find out how to style the nav bar as it's CSS which I havent done yet. 
Mistakes were made but, that is how we learn. I left the # on the about-me so the href didn't work. I also put the footer element outside of the body. I missed a closed section tag that I needed to delete. 
I tidied up the header tags as I had more than one H1 which is frowned upon. I am sure I will make that look better as I learn CSS. 
I was about to push this and I learnt that it was not saved in the GITHub repo folder so i learnt to move this to that folder via mv ~/TIL.md . I then pressed ls to check it was present, then I am free to 
git add TIL.md
git commit -m "Add TIL notes"
git push

Saturday 29th November 2025

Today I updated my about-me and coding journey paragraphs. I wanted to try making a form because I felt as if I hadn't done enough of that and needed a little refresher and put my own form on my page. I decided to make a contact-me.html and add a form on there. I remembered about adding a fieldset and legend, then the type, id and name and even that I would need a min, max, placeholder and required for the input! I just wasn't sure how to write the legend part so I asked Chat GPT to help a little. When it tells me what I will be doing next I always attempt it first then I get it to tell me how close I was rather than copying it all and not learning anything. That is the hard thing about teaching yourself, you are only cheating yourself if you aren't actively trying and testing yourself. I discovered that when I add all of that input nice and neatly on multilines, it saves and bunches it all back up to one line which I think looks messy. I asked Chat GPT if there is a way to make it so it goes one after the other under the input element and it said I need to go to settings and find force-expand-multiline. I sorted this.
I have also added a things i love.html. I have to say I am so happy with how my navigation bar works. It fills me with so much joy that when you click on the links they work!
So today I have added a name input, email input and a message input to my contact form. Made two new files, and learnt how to change my syntax to multilines. 

Sunday 30th November 2025

Today I started by adding some images to my main index.html page and the things i love page. They came out quite large so I had to add a style (in line text) to make it smaller. I am still trying to avoid any CSS for now so I can max out what can be done just using HTML. One was taller than the other so then i learnt about adding the height and object-fit:cover; This worked great. I then asked Chat GPT how I can max out what there is to learn with HTML. I tidied up my code by adding a header and main element. 
I added a books and games header to things i love and I linked my good reads profile to the goodreads logo. The file was confusing me as I didn't notice it was a JPEG instead of JPG. It didn't take me long to figure it out. 

Monday 1st December 2025

I noticed that the second photo of my pug wasn't showing on the webpage so i copied and pasted code to Chat GPt and it told me the closing "a" tag was missing. I chose to ask instead of spend lots of my time looking as I beleive AI will usually be able to help us get a lot of things done quicker. I did have the closing tag I know its not a void element so the fact I have learnt that helps me move forward quicker. 
I asked Chat GPT what else I can use using only HTML. I played around with the details element with summary and paragraph. I decided not to keep this on my page but, I enjoyed seeing what it could do. I added figure elements and figcaptions to all of my images. 