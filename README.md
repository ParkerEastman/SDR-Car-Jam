# SDR CAR JAMMER

A PoC project utilizing a simple 315MHz/433MHz jammer.

An ASK keyfob transmission is jammed w/ jammer, while transmission is recorded by SDR sink.  Dumped cap is then filtered(in the works), and retransmitted to unlock car door, while retaining unused rolling code. 

Note: this transmitter/ receiver pair did not utilize rolling codes, evinced by the continuous loop of unlock signals sent by the source cap.  In a more stringent application, filtering would be necessary, and captures could not be reused more than once. 
