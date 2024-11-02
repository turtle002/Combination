# Amino acid Combination Calculator  
## When chemists synthesize peptides, how do they identify unknown substances in mass spectra caused by the absence of one or more amino acids?  
I made a simple calculator to solve the peptide fragment problem. Before explaining what I did,Let’s explain what a peptide is.  
A peptide is composed of amino acids, the building blocks of proteins. These amino acids are linked in a specific sequence, forming a chain that defines the peptide's structure and function.  
  
![amino-acid-peptide-and-protein jpg](https://github.com/user-attachments/assets/46132367-b8f7-4c63-a879-02534e39af41)
  
Chemists can synthesize peptides and use mass spectrometry to analyze whether the peptide fragments are what we want. However, many times we can find from mass spectrometry that some unknown substances are composed of one or more amino acids missing. To quickly identify these peptides missing certain amino acids, I created a tool that can list all possible amino acid combinations of a peptide. Arrange and combine acids and calculate their molecular weights, so that chemists can immediately know that the peptide they synthesize may be missing certain amino acids.
  
For example, if a chemist synthesizes a sequence "SGDEPA" and a peak appears in the mass spectrum, its sequence is missing two amino acids, G and D. To quickly identify this peak, automatically calculate all possible combinations of amino acid molecular weights will save time in identifying unknown peaks in mass spectra caused by fragment loss.

Let’s start understanding how this program works?  
*Starting screen*  
![01](https://github.com/user-attachments/assets/15fedebe-c941-4e48-80bc-017ab5162301)  
  
*Input the amino acid sequence*  
![02](https://github.com/user-attachments/assets/54783ba1-b319-4ade-be77-cb4218b301ae)  
  
*Show the combination results*  
![03](https://github.com/user-attachments/assets/62b9ea98-dcfd-4c95-bb7e-92ee19c03ee4)  
  
### **Notes and possible changes:**  
This program only includes 20 amino acids found in nature. In the future, users will be able to enter the codes and molecular weights of non-natural amino acids.
 
 
   
