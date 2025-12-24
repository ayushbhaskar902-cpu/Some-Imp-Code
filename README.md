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
# To Sort a array and a part of a array respectively(ascending order only)
```
sort(a,a+n);
// tc nlogn
```
```
sort (a+1,a+r+1);
// sorts the array from index 1 to r
// tc nlogn

