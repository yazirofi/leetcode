class Solution {
public:
    int maximum69Number (int num) {
        string st = to_string(num);
        vector<int> arr;

        for (int i = 0; i < st.size(); i++) {
            if (st[i] == '6') {
                string s = st;
                s[i] = '9';          
                arr.push_back(stoi(s));
            }
        }
        if (arr.empty()) return num;  
        return *max_element(arr.begin(), arr.end());
    }
};
