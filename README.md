# To find the frequency of each character in a string numbered from A to Z. Note that this is for A to Z only. 
```
int freq[26] = {0};

for(char c : s) {
    freq[c - 'a']++;
}
for(int i = 0; i < 26; i++) {
    if(freq[i] > 0) {
        cout << char(i + 'a') << " -> " << freq[i] << "\n";
    }
}
```

