# :star: Network Programming

This is a repository for Tenkey to upload some codes during the experiment by [SongTian](http://cs.bit.edu.cn/szdw/jsml/fjs/st/index.htm).

Tenkey will update it occasionally.

---

### No.1 Simple & Lovely Network-Packet-Capturing Tool

This tool aims to capture network packets and unpack them, to show you on your screen and finally save those packets in a `.pcap` file which can be opened by network-packet-capture tools like Wireshark.

**Some Basic Functionalities**
- You choose which network interface yoo want to capture.
- You can set filter to get packets by conforming the Berkeley Packet Filter(BPF) syntax.
- Also you can name your `.pcap` files or it will be automatically named by the timestamp.

Codes:  [tk_cap.py](https://github.com/tenkeyseven/Network_Programing/blob/master/tk_cap.py)
