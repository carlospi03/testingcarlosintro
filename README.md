// C++ program for the count in C++ STL
// for a string
#incluide <bits/stdc++.h>
usiing namespace std;

int main()

    char vowels[5] = {´a´,´e,´,´i´,´o´´,u´,}
    
    int n=sizeof(vowels)/sizeof(vowels[0]);
    
    string str;
    
    cout<<"ingrese una palabra o frase:"<<end1;
    getline(cin,str);
    
    for(int i=0;i<n;i++)
    cout << "Number of times "<<vowels[i]<<" appears : "
         << count(str.begin(), str.end(), vowels[i])<<end1;
         
    return 0;

(https://img.shields.io/bower/v/editor.md.svg)
