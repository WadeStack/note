
在leetcode第11题看到一个题解，添加到代码前面，大幅缩减runtime


代码为：
```
static int speedup=[](){
	ios_base::sync_with_stdio(false);
	cin.tie(nullptr);
	return 0;
}();
```

leetcode11题解
```
static int speedup=[](){
	ios_base::sync_with_stdio(false);
	cin.tie(nullptr);
	return 0;
}();
class Solution
{
public:
    int maxArea(vector<int> &height)
    {
        int i = 0, j = height.size() - 1, water = 0;
        while (i < j)
        {
            int h = min(height[i], height[j]);
            water = max(water, (j - i) * h);
            while (height[i] <= h && i < j)
                i++;
            while (height[j] <= h && i < j)
                j--;
        }
        return water;
    }
};
```
