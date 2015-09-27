[あやふや] INDEX貼っただけ 1433
13:44 えんきゅー(直前 13:24:52)       13:48:19	1426	(ハッシュ)


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



