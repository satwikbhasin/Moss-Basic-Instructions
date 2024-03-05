# Moss Basic Instructions

1. Send an email to **moss@moss.stanford.edu** with the following details:
   - Leave the subject field empty.
   - In the body of the email, include:
     ```
     registeruser
     mail username@domain


     Example:
     registeruser
     mail satwikbhasin@gmail.com
     ```
   
2. Wait for 10-20 minutes (may vary) to receive a reply from moss@moss.Stanford.edu. This email will contain your Perl script.

3. Copy the script starting after the **"-----cut here-----"** text and paste it into a file named `moss.pl`.

4. Place `moss.pl` into the directory containing all your coding assignments.

5. Navigate to the same directory and execute the following command to make the script executable:
   ```
   chmod +x moss.pl        
   ```
6. Finally, execute the Perl script with the desired programming language and file extensions:
   ```
   perl moss.pl -l [coding_language] *.file_extension

   Example:
   perl moss.pl -l python *.py
   ```
