# cosc350-project-2-compressing-and-uncompressing-files-solved
**TO GET THIS SOLUTION VISIT:** [COSC350 Project 2-Compressing and Uncompressing Files Solved](https://www.ankitcodinghub.com/product/cosc350-project-2-compressing-and-uncompressing-files-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;97759&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COSC350 Project 2-Compressing and Uncompressing Files Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
# Project #2: Compressing and Uncompressing Files

## Objective

In this project you are going to implement a compression program and an uncompression

program to build a useful compression utility. These are separate programs, but they share many

functions, which should be built as shared library. The program that reads a regular file and

produces a compressed file is called the compression or huffing program. The program that does

the reverse, producing a regular file from a compressed file is called the uncompression or

unhuffing program.

## Requirements

* The huffing program should be able to perform the following operations:

* Read the characters in a text file and count the frequency of each character and store the character and its frequency in a data structure.

* Use Huffman coding algorithm to create a binary tree for Huffman coding. Your binary tree for Huffman coding should provide the following functionalities:

* Traverse the tree and record every root-to-leaf path. The edges taken for each root-to-leaf path determine the coding of the character stored in the leaf node.

* Perform a pre-order traversal to write the tree, and read it back. This is needed if the tree is stored in the header of a compressed file.

* Perform a post-order traversal to delete all tree nodes when the tree is no longer needed.

* Read the text file and produce a compressed file of the original text file. You also need to include the coding tree information at the beginning of the output file.

* The unhuffing program should be able to perform the following operations:

* Read the compressed text and the binary Huffman coding in the binary tree from the compressed file.

* Reconstruct the binary Huffman coding tree from the information read from the file.

* Use Huffman coding binary tree to create the original text file from the compressed original file.

## Note

I was unable to complete the uncompression portion the project in time for the turn in date. However, I plan to come back and complete it in my spare

time at some point.
