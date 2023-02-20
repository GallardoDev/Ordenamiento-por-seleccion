#include <iostream>
using namespace std;
int main(){

int numeros[]={5,3,1,4,2,8,6,9,0,7};
int i, j, aux, min;

for(int i=0; i < 10; i++){
    min = i;
       for(int j=i+1; j < 10; j++){
           if( numeros[j] < numeros[min]){
               min = j;
            }
        }
    aux = numeros[i];
    numeros [i] = numeros[min];
    numeros[min] = aux;
  }
cout<<"Orden ascendente:\n\n";
for(int i=0; i < 10; i++){
  cout<<numeros[i]<<" ";
}
cout<<"\n\nOrden descendente:\n\n";
for(int i=9; i>=0; i--){
    cout<<numeros[i]<<" ";
}

   return 0;
}
