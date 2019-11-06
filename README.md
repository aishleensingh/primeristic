# primeristic
amino acid codon interpreter
<html>
<head><title>Amino Acid Interpretor|Primeristic</title></head>
<body>
<center><h1><a href="C:\Users\lenovo\Desktop\cse project\primeristic.html">P R I M E R I S T I C </a></h1>
<br>
Prime Endlessly</CENTER>
<hr length=200><br>
<center><a href="C:\Users\lenovo\Desktop\primeranalyzer.html">Primer Analyzer</a>    <emsp><a href="C:\Users\lenovo\Desktop\aminoacid.html">Amino Acid Interpreter</a>    <emsp><a href="C:\Users\lenovo\Desktop\cse project\aboutus.htm">About Us</a>    <emsp></center><br>
<br>
<br>
<H3>Amino Acid Generator</H3>
<form>
Enter a codon triplet: <input type="text"><br><br>
<input type="submit"><br>
</center>
<b>What is an amino acid?</b><br>
<p>Amino acids are organic compounds that combine to form proteins. Amino acids and proteins are the building blocks of life. When proteins are digested or broken down, amino acids are left. The human body uses amino acids to make proteins to help the body: Break down food.</p>
<b>ESSENTIAL AMINO ACIDS</b><br>
<ul>
<li>Essential amino acids cannot be made by the body. As a result, they must come from food.
<li>The 9 essential amino acids are: histidine, isoleucine, leucine, lysine, methionine, phenylalanine, threonine, tryptophan, and valine.<br></ul>
<b>NONESSENTIAL AMINO ACIDS</b>

PYTHON PORTION:
#codon interpreter
c=input("Enter a codon triplet: ")
if (c=="AUG"):
  amc="Methionine/Start"
elif(c=="UUU")or(c=="UUC"):
  amc="Phenylalanine"
elif(c=="UUA")or(c=="UUG")or(c=="CUU")or(c=="CUC")or(c=="CUG")or(c=="CUA"):
  amc="Leucine"
elif(c=="AUU")or(c=="AUC")or(c=="AUA"):
  amc="Isoleucine"
elif(c=="GUA")or(c=="GUG")or(c=="GUC")or(c=="GUU"):
  amc="Valine"
elif(c=="UCA")or(c=="UCG")or(c=="UCC")or(c=="UCU")or(c=="AGC")or(c=="AGU"):
  amc="Serine"
elif(c=="GUA")or(c=="GUG")or(c=="GUC")or(c=="GUU"):
  amc="Valine"
elif(c=="CCA")or(c=="CCG")or(c=="CCC")or(c=="CCU"):
  amc="Proline"
elif(c=="ACA")or(c=="ACG")or(c=="ACC")or(c=="ACU"):
  amc="Threonine"
elif(c=="GCA")or(c=="GCG")or(c=="GCC")or(c=="GCU"):
  amc="Alanine"
elif(c=="UAU")or(c=="UAC"):
  amc="Tyrosine"
elif(c=="UAA")or(c=="UAG")or(c=="UGA"):
  amc="STOP"
elif(c=="CAC")or(c=="CAU"):
  amc="Histidine"
elif(c=="CAA")or(c=="CAG"):
  amc="Glutamine"
elif(c=="AAU")or(c=="AAC"):
  amc="Asparagine"
elif(c=="AAA")or(c=="AAG"):
  amc="Lysine"
elif(c=="GAU")or(c=="GAC"):
  amc="Aspartic Acid"
elif(c=="GAA")or(c=="GAG"):
  amc="Glutamic Acid"
elif(c=="UGU")or(c=="UGC"):
  amc="Cysteine"
elif(c=="UGG"):
  amc="Tryptophan"
elif(c=="CGA")or(c=="CGG")or(c=="CGC")or(c=="CGU")or(c=="AGG")or(c=="AGA"):
  amc="Arginine"
elif(c=="GGA")or(c=="GGG")or(c=="GGC")or(c=="GGU"):
  amc="Glycine"
print("Amino acid for given codonn is: ",amc)
