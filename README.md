1. Datormācība (pamatkurss) elektroniskā klade
2. 'Shell commands'
3. history
4. VirtualBox --startvm XP
5. quartus
6. firefox & (open browesr firefox )
7. exit
8. uname (Выводит некую основную информацию о системе. если задать параметр -a , можно получить информацию о ядре, имени хоста и узнать архитектуру процессора)
9. uname -a
10. echo
11. echo $0
12. sh
13. man uname  (Команда выводит имя пользователя)  
14. whoami(отображает собственное имя пользователя)
15. who (сообщает информацию о пользователе)
16. last (лог заходящих в систему)
17. pdw
18. pwd (выводит путь к текущей папке)
19. clear (очистить командную строку) 
20. pwd
21. /home
22. /user
23.history   
24. ash  (Almquist shell)
25. man + command (описание комманды)   
26. tty  (print the file name of the terminal connected) 
27. **Shortcut Keys** 
28. cntr + shift +,+F1,F2,F3,F4,F5,F6,F7 (switching between virtual terminals)
29. cntr+,- (увиличение или же уменьшение командной консоли) 
30. ctrl+alt (p,f,h)
31. ctrl+L  (clean terminal screen)

 2  quartus  
 3  ls  
 4  mkdir ABC  
 5  ls -l  
 6  cd ABC/  
 7  wpd  
 8  pwd  
 9  tree  
 10  cd  
 11  pwd  
 12  cd exit  
 13  cd..  
 14  cd ..  
 15  ls -la  
 16  cd ..  
 17  ls -la  
 18  pwd  
 19  cd.  
 20  celar  
 21  clear  
 22  man ls  
 23  cd ABC/  
 24  pwd  
 25  mkdir ABC (create new folder)  
 26  cd ABC/ (open)  
 27  pwd  
 28  tree (tree of all folders)  
 29  pwd  
 30  cd .  
 31  pwd  
 32  cd ..  
   35  whoami  
   36  who  
   37  pwd  
   38  ls  
   39  ls -a  
   40  man ls  
   42  ls -a -l  
   44  ls -al  
   47  tree  
   48  clear  
   49  pwd  
   50  cd ABC  
   51  pwd  
   52  tree  
   53  cd .  
   54  wpd  
   55  pwd  
   56  cd ..  
   57  pwd  
   58  ls  
   59  cd ABC  
   60  pwd  
   61  cd ..  
   62  ls -la    
   63  pwd     
   64  cd    
   65  pwd  
   66  cd /  
   67  pwd  
   68  cd /home/user/  
   69  pwd  
   70  cd ~  
   71  pwd  
   72  clear  
   73  pwd  
   74  ls  
   75  rmdir ABC/ (delete folder)  
   76  ls  
   77  clear  
   78  mkdir EFG  
   79  mkdir HIJ  
   80  ls -l  
   82  touch a.txt (black folder)  
   83  ls -lt  
   86  echo (repeat)   
   87  echo dkfgjdklfw  
   88  echo 12345 > b.txt  
   89  ls -ls  
   90  ls -lt  
   91  echo 12345 > b.txt  
   92  ls -lt  
   94  cat b.txt (reading text file)  
   95  echo 67890 > b.txt  
   96  ls -lt  
   97  echo abcde >> b.txt  
   98  ls -lt  
   99  cat b.txt  
  100  echo fghij >> c.txt  
  101  ls -lt  
  102  clear  
  103  nano d.txt (opening modified menu)  
  104  hexdump -C dd.txt  
  105  ls -lt  
  106  rm a.txt (file delete)  
  107  mv HIJ KLM  
  108  ls -lt  
  109  clear  
  110  mv b.txt b.text  
  111  ls -lt  
  112  rm *.txt (delete all txt)  
  113  ls -lt  
  114  clear  
  115  pwd  
  116  ls -lt  
  117  cp b.text ./KLM/b1.text  
  118  ls -lt  
  119  rm b.text  
  120  ls -lt  
  121  cp KLM/b1.text EFG/b2.txt  
  122  ls -l KLM/  
  123  ls -lt  
  124  ls -l KLM/  
  125  cd KLM/  
  126  ls -lt  
  127  /KLM$ ls -lt  
  128  cat b1.text  
  129  pwd    
  130  ls -l  
  133  ls -l /home/user/EFG  
  134  pwd  
  135  ls -l ../EFG  
  136  ls -l /home/user/EFG  
  137  ls -l ../EFG  
  138  pwd   
  139  ls -lt  
  140  rmdir EFG/  
  141  ma rmdir  
  142  clear  
  143  man rmdir  
  144  rmdir --ignore-faol-on-non-empty  
  145  man rm  
  146  rm -r EFG/  
  147  ls -l  
  148  ls -lt  
  149  rm -r EFG  
  150  ls -lt  
  151  rm -r KLM/  
mkdir ABC//make directory w name ABC  
 cd ABC/ //change directory to ABC  
 cd //home  
 cd . //enter folder  
 cd .. //exit folder  
cd / //root  
 cd ~ //home  
 rmdir ABC //remove directory w/o files inside  
 touch a.txt // make txt file w name a  
 cat (file name).txt // read txt files  
 > //writes text in files if there already is text replaces it  
 >> //adds text in txt file  
 nano (name.txt) //text redactor  
 hexdump -C (name.txt) //show hex code  
 rm (name.txt) // removes file -r //removes dir + files inside  
 mv (WHAT) (WHERE) //move + rename  
 cp name.text DIR/othername.text //copy  
 ls -lt ../DIRNAME //look into other folder w/o closing already used directory  
 
 pwd  
    5  echo $echo  
    6  ls download  
    7  ls download/  
    8  echo $?  
    9  nano a.sh  
   10  wpd  
   11  pwd  
   12  ls -  
   13  ls -l  
   14  git clone  
   15  history  



 PU1/PT1: 40 000 000 000   
void main()    
{  
  
  printf ("Mainigo reizinasana: a x b\n");  
  scanf ("%ld",&a);  
  printf ("Mainigais - a vertiba = %ld\n ,a);  
long int b;  
  printf ("Pieskirt vertibu mainigajam - b :");  
  scanf ("%ld" ,&b);  
  printf ("Mainigais - a vertiba == %ld\n" ,b);  
  
long int c=a*b;  
  printf ("%ld x %ld = %ld\n" ,a,b,c);  
  
PU3/PT3: if + simple sort  

int  sim_g = 0;          // izveleta simblu grupa  
char simb_1 = 0;        // Definetasis simbols Nr. 1  
char simb_2 = 0;        // Definetasis simbols Nr. 2  
char simb_3 = 0;        // Definetasis simbols Nr. 3  
int  sec = 0;           //seciba (augosa vai dilstosa).  
   
  
int allsimbs (){   
printf("\n\n\n");    
printf("        Ievietojiet simbolus individuali atdalot tos (lai apstiprinatu izvaleto simbolu nospiest - ENTER)\n");  
printf("                        simbolu skaits ir limitets Max 3 individuali simboli\n\n\n");  
printf("        Definejiet simbolu Nr. 1\n      (Lai apstiprinatu ievietoto simbolu nospiest - ENTER) : ");  
scanf("%s",&simb_1);  
  
        if(simb_1 != 0){  
        printf("\n\n");    
        printf("        Definejiet simbolu Nr. 2\n      (Lai apstiprinatu ievietoto simbolu nospiest - ENTER) : ");  
        scanf("%s",&simb_2);  
        }   
                if(simb_2 != 0){  
                printf("\n\n");  
                printf("        Definejiet simbolu Nr. 3\n      (Lai apstiprinatu ievietoto simbolu nospiest - ENTER) : ");  
                scanf("%s",&simb_3);  
                }  
                        if(simb_3 != 0){  
                        printf("\n\n");  
                        printf("        Definetie simboli\n\n Nr. 1 :	%c\n Nr. 2 :	%c\n Nr. 3 :	%c\n", simb_1, simb_2, simb_3);  
                        }  
  
return 0;  
}//int allsimbs  
  
  
int main()  
{  
printf("\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n");  
printf("						Dotos simblu sakartosana augosi vai dilstosi\n\n\n\n\n");  
printf("		Izveleties simbolu grupu\n\n\n");  
printf("			Ja velaties sakartot simbolus grupu 1. - latinu ALFABETA no A lidz Z\n\n");  
printf("			Sadala: (Define simbolu grupu) ievieto : 1\n\n\n\n\n");  
printf("			Ja velaties sakartot simbolus grupu 2.- vesali SKAITLI no 0 lidz 9\n\n");  
printf("			Sadala: (Define simbolu grupu) ievieto : 2\n\n\n\n\n");  
printf("               	Define simblu grupu (lai apstiprinatu izvaleto grupu nospiest - ENTER) : ");  
  
  
	scanf("%d",&sim_g);  
	 if(sim_g == 1){   
	printf("\n\n\n\n");  
      	 printf("		izveleta grupa - ALFABETA no A lidz Z\n");  
	 }  
  
	 if(sim_g == 2){  
        printf(" \n\n\n\n");  
	 printf("		izveleta grupa - SKAITLI no 0 lidz 9\n");  
	 }  
  
	 if(sim_g != 1 && sim_g != 2){  
        printf("\n\n\n\n");  
	printf("		Neeksistejosa simbolu grupa\n\n\n\n\n");  
	}  
  
if(sim_g <= 2){  
  
 allsimbs();  
  
        printf("\n\n\n");  
        printf("	Definejiest secibu kada tiks sakartoti simboli ");  
        printf("\n\n\n");  
        printf(" 		Lai definetos simbolus skartoto DILSTOSI sadala\n \n	Seciba noradi : 1");  
        printf("\n\n\n");  
        printf(" 		Lai definetos simbolus skartoto AUGOSI sadala\n \n 	Seciba noradi : 2");  
	printf("\n\n\n");  
        printf("      	        Seciba - (Lai apstiprinatu izveleto secibu nospiest - ENTER) : ");  
	scanf("%d",&sec);  
  
if(sec == 1){ //Augosa seciba  

	if(simb_1 > simb_2 && simb_1 > simb_3){  
		if(simb_3 > simb_2){  
			printf("\n");  
			printf("Dilstosa seciba\n\n 	%c\n 	%c\n 	%c\n",simb_1, simb_2, simb_3);  
		}  
		else{  
			printf("\n");  
			printf("Dilstosa seciba\n\n	%c\n 	%c\n 	%c\n",simb_1, simb_3, simb_2);  
		}  
	}  
	if(simb_2 > simb_1 && simb_2 >simb_3){  
		if(simb_3 > simb_1){  
			printf("\n");  
			printf("Dilstosa seciba\n\n 	%c\n 	%c\n 	%c\n",simb_2, simb_3, simb_1);  
		}  
		else{  
			printf("\n");  
			printf("Dilstosa seciba\n\n 	%c\n 	%c\n 	%c\n",simb_2, simb_1, simb_3);  
		}  
	}  
        if(simb_3 > simb_1 && simb_3 > simb_2){  
                if(simb_2 > simb_1){  
                        printf("\n");  
                        printf("Dilstosa seciba\n\n 	%c\n 	%c\n 	%c\n",simb_3, simb_2, simb_1);  
                }  
                else{  
                        printf("\n");  
                        printf("Dilstosa seciba\n\n	%c\n 	%c\n 	%c\n",simb_3, simb_1, simb_2);  
    
		}  
	}  
printf("\n\n\n");  
}//if augosa seciba  
  
if(sec == 2){ //Dilstosa seciba  
  
        if(simb_1 < simb_2 && simb_1 < simb_3){  
                if(simb_3 < simb_2){  
                        printf("\n");  
                        printf("Augosa seciba\n\n 	%c\n	 %c\n	 %c\n",simb_1, simb_2, simb_3);  
                }  
                else{  
                        printf("\n");  
                        printf("Augosa seciba\n\n 	%c\n	 %c\n	 %c\n",simb_1, simb_3, simb_2);  
                }  
        }  
        if(simb_2 < simb_1 && simb_2 < simb_3){  
                if(simb_3 < simb_1){  
                        printf("\n");  
                        printf("Augosa seciba\n\n 	%c\n 	%c\n	 %c\n",simb_2, simb_3, simb_1);  
                }  
                else{  
                        printf("\n");   
                        printf("Augosa seciba\n\n 	%c\n	 %c\n	 %c\n",simb_2, simb_1, simb_3);  
                }  
        }    
        if(simb_3 < simb_1 && simb_3 < simb_2){  
                if(simb_2 < simb_1){   
                        printf("\n");  
                        printf("Augosa seciba\n\n 	%c\n	 %c\n	 %c\n	",simb_3, simb_2, simb_1);  
                }  
                else{
                        printf("\n");  
                        printf("Augosa seciba\n\n	%c\n 	%c\n 	%c\n"	,simb_3, simb_1, simb_2);  
  
                }  
        }  
}//if dilstosa seciba  
  
}//if noradita kada no dotajam grupam  
  
if(sec != 1 && sec != 2){  
	printf("\n");  
	printf("\n");  
	printf("		Nav noradita Seciba kada sakartor sibolus");  
	printf("\n");  
	printf("\n");  
}  
return 0;  

 
 

