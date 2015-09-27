mysql -h localhost -P 3306 -u root isucon5q


# [あやふや] INDEX貼っただけ 1433
# 認証を簡略化 1426	(ハッシュ)

isucon@hosoda-isucon5q:~/webapp/config$ sudo python ../summary_log.py /tmp/nginx-access.log
Request by count
316 GET /
264 GET /diary/entries/*
262 GET /diary/entry/*
259 GET /profile/*
113 POST /login
110 GET /login
108 GET /friends
90 POST /diary/comment/*
90 GET /logout
88 GET /footprints
86 POST /diary/entry
10 POST /friends/*
2 GET /css/bootstrap.min.css
1 POST /profile/*
1 GET /initialize

Request by total time
274.603 0.868996835443 GET /
11.515 0.0436174242424 GET /diary/entries/*
6.262 0.0579814814815 GET /friends
3.26 0.0125868725869 GET /profile/*
2.79 0.0317045454545 GET /footprints
1.39 0.00530534351145 GET /diary/entry/*
0.465 0.00411504424779 POST /login
0.262 0.00291111111111 POST /diary/comment/*
0.184 0.00213953488372 POST /diary/entry
0.063 0.000572727272727 GET /login
0.063 0.0063 POST /friends/*
0.041 0.000455555555556 GET /logout
0.019 0.019 GET /initialize
0.004 0.002 GET /css/bootstrap.min.css
0.001 0.001 POST /profile/*

Request by out bytes
17209664 65188 GET /diary/entries/*
5278944 16705 GET /
1697966 15721 GET /friends
1091247 4213 GET /profile/*
788484 3009 GET /diary/entry/*
735469 8357 GET /footprints
131770 1197 GET /login
122901 61450 GET /css/bootstrap.min.css
50674 448 POST /login
35995 399 GET /logout
18718 207 POST /diary/comment/*
18454 214 POST /diary/entry
1970 197 POST /friends/*
211 211 POST /profile/*
170 170 GET /initialize

# UNIX domain SOCKET 1368
まえ: 14:21:36


```
isucon@hosoda-isucon5q:~/webapp/config$ sudo python ../summary_log.py /tmp/nginx-access.log
Request by count
303 GET /
252 GET /diary/entry/*
252 GET /diary/entries/*
250 GET /profile/*
107 GET /login
107 POST /login
101 GET /friends
86 POST /diary/comment/*
86 GET /logout
83 POST /diary/entry
83 GET /footprints
9 POST /friends/*
2 GET /css/bootstrap.min.css
1 POST /profile/*
1 GET /initialize

Request by total time
279.718 0.923161716172 GET /
11.446 0.0454206349206 GET /diary/entries/*
6.043 0.0598316831683 GET /friends
3.458 0.013832 GET /profile/*
2.639 0.0317951807229 GET /footprints
1.231 0.00488492063492 GET /diary/entry/*
0.246 0.00286046511628 POST /diary/comment/*
0.23 0.00214953271028 POST /login
0.221 0.00266265060241 POST /diary/entry
0.073 0.073 GET /initialize
0.067 0.00744444444444 POST /friends/*
0.064 0.000598130841121 GET /login
0.044 0.000511627906977 GET /logout
0.003 0.0015 GET /css/bootstrap.min.css
0.001 0.001 POST /profile/*

Request by out bytes
16624679 65970 GET /diary/entries/*
5037423 16625 GET /
1591741 15759 GET /friends
1050903 4203 GET /profile/*
709930 2817 GET /diary/entry/*
695864 8383 GET /footprints
128181 1197 GET /login
122901 61450 GET /css/bootstrap.min.css
46224 432 POST /login
34395 399 GET /logout
18175 218 POST /diary/entry
17881 207 POST /diary/comment/*
1773 197 POST /friends/*
209 209 POST /profile/*
170 170 GET /initialize
```
