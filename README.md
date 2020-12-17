# transfer

tc_sock = socket.socket(socket.AF_INET, socket.SOCK_DGRAM)tc_sock.bind((outgoing_if, tc_local_port))tc_sock.sendto(b"\xaa"*8, (remote_tc_host,tc_remote_port)
