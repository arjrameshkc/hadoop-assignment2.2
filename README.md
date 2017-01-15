# hadoop-assignment2.2
[acadgild@localhost ~]$  cat ramesh/max-temp.txt
10-01-1990,20
12-02-1991,22
23-12-1992,27
12-05-1993,30
10-04-1994,29
12-03-1995,25
25-02-1996,24
12-06-1997,26
10-07-1998,27
20-08-1999,28
27-09-2000,29
12-06-2001,26
10-07-2002,27
20-08-2003,28
27-09-2004,29
10-07-2005,27
20-08-2006,28
27-09-2007,29

[acadgild@localhost ~]$  hadoop fs -copyFromLocal ramesh/max-temp.txt /user/acadgild/hadoop/max-temp.txt
17/01/15 17:06:00 WARN util.NativeCodeLoader: Unable to load native-hadoop library for your platform... using builtin-java classes where applicable
[acadgild@localhost ~]$  hadoop fs -cat /user/acadgild/hadoop/max-temp.txt17/01/15 17:06:49 WARN util.NativeCodeLoader: Unable to load native-hadoop library for your platform... using builtin-java classes where applicable
10-01-1990,20
12-02-1991,22
23-12-1992,27
12-05-1993,30
10-04-1994,29
12-03-1995,25
25-02-1996,24
12-06-1997,26
10-07-1998,27
20-08-1999,28
27-09-2000,29
12-06-2001,26
10-07-2002,27
20-08-2003,28
27-09-2004,29
10-07-2005,27
20-08-2006,28
27-09-2007,29

[acadgild@localhost ~]$  hadoop fs -chmod 644 /user/acadgild/hadoop/max-temp.txt
17/01/15 17:07:26 WARN util.NativeCodeLoader: Unable to load native-hadoop library for your platform... using builtin-java classes where applicable
[acadgild@localhost ~]$  hadoop fs -cat /user/acadgild/hadoop/max-temp.txt17/01/15 17:08:01 WARN util.NativeCodeLoader: Unable to load native-hadoop library for your platform... using builtin-java classes where applicable
10-01-1990,20
12-02-1991,22
23-12-1992,27
12-05-1993,30
10-04-1994,29
12-03-1995,25
25-02-1996,24
12-06-1997,26
10-07-1998,27
20-08-1999,28
27-09-2000,29
12-06-2001,26
10-07-2002,27
20-08-2003,28
27-09-2004,29
10-07-2005,27
20-08-2006,28
27-09-2007,29

