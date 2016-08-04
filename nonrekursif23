#include <iostream.h>
#include <conio.h>

long int faktorial( long int a);

main(){
 long int faktor;
 long int n;
   cout<<"Masukan Nilai Faktorial ";
   cin>>n;
   faktor = faktorial(n);
   cout<<n<<"! = "<<faktor<<endl;
   getch();
}

long int faktorial( long int a){
   if(a==1 || a==0){
    return(1);
   }else if (a>1){
    return(a*faktorial(a-1));
   }else{
    return(0);
   }
}
