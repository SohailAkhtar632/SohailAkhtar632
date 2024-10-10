lass Solution {
  public:
    int findElementAtIndex(int key, vector<int> &arr) {
        // code here
        for(int i=0;i<arr.size()-1;i++){
            if(key==arr[i]) key=arr[i];
        }
        return arr[key];
    }
};
