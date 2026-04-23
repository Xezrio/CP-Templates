1. string从1开始：s = ' ' + s;

2. fill(a, a+N, 0);

3. 更新mex值的技巧：

    ​	bool have[N];

    ​	have[a[i]] = true;

    ​	while(have[mex]) mex++;

4. x = (x % mod + mod) % mod     对正负数x取模mod

