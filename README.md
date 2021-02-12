# PoC Adobe Reader JP2K parsing OOB write - DoS

This is the result of an incomplete fix for a previous OOB write bug related to JP2K parsing. I believe it's just a DoS cause the offset from page zero can't be manipulated and in user mode you can't map stuff at page zero.
