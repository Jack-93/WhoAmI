# Greetings! This is introduction of me, Jack
  [![Tech Blog Badge](http://img.shields.io/badge/-Tech%20blog-black?style=flat-square&logo=github&link=https://Jack-93.github.io/)](https://Jack-93.github.io/)	
  [![Instagram Badge](https://img.shields.io/badge/Insta-ff0010?style=flat-square&logo=Instagram&link=https://https://www.instagram.com/zig_jack93/)](www.instagram.com/zig_jack93/)
  [![Gmail Badge](https://img.shields.io/badge/Gmail-d14836?style=flat-square&logo=Gmail&logoColor=white&link=mailto:worl5@korea.ac.kr)](mailto:worl5@korea.ac.kr)

  ### Worst To Better
  ### Lotto Is Best
 

```c

#include <iostream>
using namespace std;

int main(){
  int num[45]={};

  for(int i=0;i<45;i++){
    num[i]=i+1;
  }
    int temp,index1,index2;
    for (int i = 0; i < 100; i++)
    {
        index1 = rand() % 45;
        index2 = rand() % 45;
        temp = num[index1];
        num[index1] = num[index2];
        num[index2] = temp;
    }
    for (int i = 0; i < 6; i++)
    {
        cout << (i + 1) << "번째 번호 : " << num[i] << "\n";
    }
    cout << "이번 주 로또 번호는 !: "<< num[0] << ", " << num[1] << ", " << num[2] << ", " << num[3] << ", "
     << num[4] << ", " << num[5] << "\n";
    return 0;
}
```

