python /home/htzy/server/Bin/SocketPolicyServer/SockPol.py --file=sockpolicy.xml --port=843
python -c 'print "<policy-file-request/>%c" % 0' | nc 127.0.0.1 843
