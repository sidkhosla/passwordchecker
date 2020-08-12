# passwordchecker
This script works best when ran from the terminal. 
def request_api_data(query_char): This function requests api data from pwnedpasswords.com.
def get_password_leaks_count(hashes, hash_to_check):This function requests for the count of password leaked iterations. It uses the tail and hasshed password genrated by the 3rd function.
def pwned_api_check(password): This function converts the password in the SHA1 format.
def main(text): This uses the sys module which recives the file name argument from the terminal.