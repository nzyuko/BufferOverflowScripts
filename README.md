# For CTF reference with skeleton exploit code (Python2)
The fuzz.py script will send \x41 (A) incrementally, 100 bytes at a time to port a specified port until it's no longer able to communicate with that port. That way we can ascertain that it has crashed has crashed
