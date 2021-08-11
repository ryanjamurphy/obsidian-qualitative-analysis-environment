# Guide to using this environment

The core idea of this [Obsidian](https://obsidian.md) vault: take each of the pieces of text you're working with, make it easy to traverse them, and add in ways of coding them and writing up what the codes mean.

This environment was built with a [grounded field theory](https://fulcra.design/a-brief-informal-guide-to-doing-grounded-theory) approach in mind. Deeply read each data point, highlighting the key points and looking for commonalities and oddities. As those interesting phenomena emerge, cluster and describe them under themes (also called “codes”). Check each theme/insight against one another and refine them to reduce redundancy as needed. Once the data has been thoroughly reviewed, quantify the number of responses attributed to each of the themes in order to get a sense of the most and least common themes. A final report based on this analysis might consist of a ranked list of these themes, sorted by how often they were reported, a description of each theme, and a selection of illustrative responses for them from students. 

## Setting up the environment
1. Install Obsidian, if you haven't already. See https://obsidian.md for the latest releases.
2. [Download the starter environment from GitHub](https://github.com/ryanjamurphy/obsidian-qualitative-analysis-environment).
1. Extract the downloaded kit wherever you'd like on your computer.
2. Open Obsidian, open the [Vault Picker](https://help.obsidian.md/How+to/Working+with+multiple+vaults) (the little vault icon in the bottom-left), and open the newly-extracted folders.
3. To use all of this environment’s functionality, you have to disable Safe Mode in the vault (because it uses some community plugins). To do this, go to Preferences → Community Plugins and turn Safe Mode off.

### Preparing the data
First, make every data point its own markdown (`.md`) file, naming them sequentially starting at 1. 

Find the subfolder in this vault folder called "data points" (or rename it to whatever you'd like). Place all of your data points in this folder.

Putting the data points in each of their own files and numbering them sequentially is a trick: it allows us to use the core Daily Note plugin's "Next Daily Note" and "Previous Daily Note" commands to quickly traverse the responses. So, set those two commands to an easy-to-reach hotkey (I used <kbd>cmd</kbd>+<kbd>alt</kbd>+<kbd>→/←</kbd>. You will be using these commands at least once for every piece of data you're analysing!

Second, find the folder in called "codes". In your new Obsidian vault, go to `Preferences → Files & Links → Default Location for New Notes`, and change this to your “codes” folder. This will mean that every new note you create from links or from the "New note" command will show up in this folder. 

### Coding the data
Open the first data point—the file in the "data points" folder named "1". 

Below the text data, add a footer. You could use a heading (e.g., `## Coding`). I just left a couple of new lines between the data itself and where I was putting the codes. In this footer, you will simply list each of the themes you identify in the data point.

Review the data. What does it say? What's interesting about it? How might it help you answer your research question(s)? Think of the answers to these questions as themes: they are the interesting takeaways relevant to this piece of data. In the footer, write out these themes.

Here's the secret to making this whole set-up work: add each code as an internal `[[`link`]]`. That affords us several things:
- Codes are suggested when you start a new internal link `[[`, so that we can choose from the options instead of trying to recall them.
- The individual responses will be structurally related to the codes via backlinks (and visually linked to the codes via the graph view).
- Editing a code by renaming it will propagate the change to that code throughout the data.
- Finally, it makes codes themselves an object we can add information to. You can open a code-as-link as a note and describe it, embed exemplary instances of the coding from the responses, and so on.

You may want to keep a [[Code Index]], just to provide an easy place to organize and see all the codes you've identified at once. In the code Index, list each code you add to your data. Feel free to order them under headings or however else you'd like!

Once you've finished reading this data point and adding themes, move onto the next one by using the Next Daily Note command (or tapping the hotkey you assigned earlier).

### Analyzing the data
When using grounded field theory, you should incrementally update, revise, and refine your theory—your encoding—as you review the data. The goal is to render visible all of the interesting insights that lie inside your data, to clearly explain what those findings are, and to continually check and re-check them as you continue to review your data. 

That means that as you review more and more data, you're doing four things:
1. labelling the data points with the themes you've identified already;
2. creating new themes to call-out anything new in the data point you haven't already picked up on; 
3. refining existing themes by (a) summarizing and adding detail to them (commonly referred to as writing memos about the themes), (b) embedding particularly illustrative examples of them in the data, (c) splitting up themes if they actually contain different important ideas, and (d) combining themes if they are significantly overlapping; and
4. as necessary, looking for themes of themes: clusting and structuring the insights you've found inasmuch as the clustering makes your takeaways clearer or more impactful.

### Reporting on the data
Once you've reviewed all the data at least once, you should have a set of themes clustering the different data points by the interesting insights they contain. You may want to go back through the data—or the themes, or the specific subsets of the data—more than once to refine your analysis further (see analysis steps 1-4 above). Once you feel satisfied with the takeaways, it's time to write it up.

#### Quantifying your themes
An easy thing to do is quantify the number of data points associated with each theme. This gives you a quick estimate of how frequent or common these takeaways are found in your data. 

There are many many ways you may quantify the number of data points per theme. The simplest is just to use Obsidian's core Search functions. For each theme, enter `"[[` followed by the exact name into your search, then end the search query with `]]"`. This will search for exact mentions of the linked theme. Once the search has finished, tap on the Copy Search Results button above the search query text box. Last, in the options presented to you, change the List Prefix to "Numbered." This gives you a count for the number of results for each theme.

However, that could be tedious if you have a lot of themes to count. Instead, this environment uses the Dataview plugin. See the [[Statistics]] page.

This generates a table listing each theme, the number of data points associated with that theme, and the number of other themes you've linked to that theme (if you have done so at all). 

When reporting on your themes, these counts give you some starting points. Why do the top themes appear so frequently? Why are the bottom ones rare? Speculate, theorize, debate, and discuss!

#### Writing up each theme
It's your job to report on the relevance of the themes you've uncovered to your research question(s). The memos you've already developed about each theme give you a starting place for commentary. Build on those, and use any exemplary cases you've embedded to illustrate your points. If you need to look back at your data, the backlinks from your themes will point to all of the data points you coded with a given theme. 

You may also want to examine themes that seem to have common data points in mind. Why did these overlaps happen? What might they mean? 

As you sift through your data to develop your ideas and arguments, it may help to open many notes at once so that you can quickly refer to each. 

### Conclusion
That's all! Enjoy.