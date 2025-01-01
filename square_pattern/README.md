#include <iostream>
using namespace std;

void printsquare(int width,int height){
    for(int i = 0; i < hieght; i++ ){
      for (int j = 0; j < width; i++){
        cout << "*";
      }
    cout<<endl;
    
    }
}

  int main(){
    int width, height;
    cout<< "Enter the wigth of the square: ";
    cin>> width;
    cout<< "Enter the height of the square: ";
    cin>> height;

    printSquare(width, height);
  
    return 0;
  }
