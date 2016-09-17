#Comandos Unix

---

##echo "Hola mundo"

##echo "Hola $USER"

---

##ls

##ls -l

##ls -la

---

##mkdir Dir

---

##rm -r Dir

---

##X="Cosme"

##echo $X

---

##> new.txt
##echo "" > new1.txt
##touch new2.txt

---

##hidden="ls -la"
##$hidden

---
##if [ operand operator operand ]
##then
##echo "true"
##else
##echo "false"
##fi

---
<table border="5" cellpadding="5">
<tbody><tr><td>operator</td><td>produces true if... </td><td>number of operands</td>
</tr>
<tr><td>-n</td><td>operand non zero length</td><td>1</td>
</tr>
<tr><td>-z</td><td>operand has zero length</td><td>1</td>
</tr>
<tr><td>-d</td><td>there exists a directory whose name is <em>operand</em></td><td>1</td>
</tr>
<tr><td>-f</td><td>there exists a file whose name is <em>operand</em></td><td>1</td>
</tr>
<tr><td>-eq</td><td>the operands are integers and they are equal</td><td>2</td>
</tr>
<tr><td>-neq</td><td>the opposite of -eq</td><td>2</td>
</tr>
<tr><td>=</td><td>the operands are equal (as strings)</td><td>2</td>
</tr>
<tr><td>!=</td><td>opposite of = </td><td>2</td>
</tr>
<tr><td>-lt</td><td><em>operand1</em> is strictly less than <em>operand2</em> (both operands should be integers)</td><td>2</td>
</tr>
<tr><td>-gt</td><td><em>operand1</em> is strictly greater than <em>operand2</em> (both operands should be integers)</td><td>2</td>
</tr>
<tr><td>-ge</td><td><em>operand1</em> is greater than or equal to <em>operand2</em> (both operands should be integers)</td><td>2</td>
</tr>
<tr><td>-le</td><td><em>operand1</em> is less than or equal to <em>operand2</em> (both operands should be integers)</td><td>2</td>
</tr>

</tbody></table>

---
##for x in *
##do
##echo $x
##done

##for x in 1 2 3 4 5
##do
##echo $(($x+2))
##done

---

##La mejor referencia de ciclos en bash
> [ciclos](http://www.cyberciti.biz/faq/bash-for-loop/)

---

##A practicar! (*ind)
[hackerrank](https://www.hackerrank.com/domains/shell/bash)

---
#Arrays

##arr=(1 2 3 4 5 6)
##echo ${arr[*]}
##arr[2]="a"

##A practicar! (*pair)
[hackerrank](https://www.hackerrank.com/domains/shell/arrays-in-bash/difficulty/all/page/1)

---
##Pipes
##command  | command | command

---
##Grep
##cat LICENSE
##grep GNU LICENSE
##grep -r hola .

---
#Procesamiento de texto

## cut -c 1-5
## paste
## tail
## head
---

##A practicar! (*pair)
[hackerrank](https://www.hackerrank.com/domains/shell/textpro)

---
##sed, awk
##echo -e "A,2\nB,8" > sum.txt
##sed -i '1s/^/C,12\n/' sum.txt
##awk 'BEGIN {FS= ","; i=0; tot=0};{ i+=1; tot+=$2} END {print tot/i}' sum.txt

---

##A practicar! (*ind)
[hackerrank](https://www.hackerrank.com/domains/shell/grep-sed-awk/difficulty/all/page/1)
