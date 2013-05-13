lxc-status
==========


A simpler helper python script to see lxc resource usage

Example output:

    bekir@host:~$ sudo ./lxc-status
               name   mem  mem_lim  mem%  read  wrote  read#  wrote#    cpu cpu#
    --------------- ----- -------- ----- ----- ------ ------ ------- ------ ----
                api    1G       4G 27.15   48K    48K     12      12   530G    2
          appserver  884M       8G  10.8   48K    48K     12      12   510G    4
               ping  582M       1G 56.85   40K    40K     10      10   524G    1
         monitoring  869M      16G   5.3   56K    56K     14      14   542G    4
           database    9G      16G 61.06    1M     1M    272     272   774G    8
              redis  528M      16G  3.22   48K    48K     12      12   701G    4
    bekir@host:~$ 
