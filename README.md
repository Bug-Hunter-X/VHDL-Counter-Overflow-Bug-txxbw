# VHDL Counter Overflow Bug

This repository demonstrates a common error in VHDL code: an integer overflow in a counter.  The `buggy_counter.vhdl` file contains the faulty code, while `fixed_counter.vhdl` provides the corrected version.  The bug involves incorrect handling of the counter's rollover from its maximum value back to 0.  The solution utilizes more robust techniques to prevent this issue.  This example is useful for illustrating proper integer handling in VHDL and highlighting the importance of careful boundary condition consideration. 