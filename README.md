# NCHSDrumshow2022
Instructions for NCHSDrumshow

This code is for the dropdown menu on the About the Cast Page. Because there is no widget for a dropdown menu, I used some existing code for a dropdown button and customized it for the NCHS Drumshow page. If you would like to edit the code by adding new options to the dropdown menu, I would recommend taking the code from here, editing it in a .txt file editor, then copy/pasting that into the text editor for the About the Cast page. 

In order to add new links, this is what you should do: 

find this section of the code:

'''

<button class="dropbtn">Select Year</button>
<div class="dropdown-content"><a href="https://www.nchsdrumshow.com/2022cast">2022</a>
<a href="https://www.nchsdrumshow.com/2020cast">2020</a>
<a href="https://www.nchsdrumshow.com/2019cast">2019</a>
<a href="https://www.nchsdrumshow.com/2018cast">2018</a>
<a href="https://www.nchsdrumshow.com/2017cast">2017</a>
</div>
</div>

'''

Before the </div> directly after the last link, you can add in a new link like so: 

<a href="LINK HERE">YEAR</a>

That will add a new link to the dropdown menu. 

The code snippet is in this repository EXACTLY how it should look in the text editor on the page. If there is anything that looks different in that code, it will break the button. In that case, I would recommend just copy and pasting the code from here over there, or, if you have edited it to add more links, to copy/paste it from that .txt file, into the text editor while removing everything else that is currently in there. This will not delete your work if you have it all saved separately, but will reset the page so that the button looks right. 
