


███████╗███╗░░░███╗░█████╗░██╗██╗░░░░░
██╔════╝████╗░████║██╔══██╗██║██║░░░░░
█████╗░░██╔████╔██║███████║██║██║░░░░░
██╔══╝░░██║╚██╔╝██║██╔══██║██║██║░░░░░
███████╗██║░╚═╝░██║██║░░██║██║███████╗
╚══════╝╚═╝░░░░░╚═╝╚═╝░░╚═╝╚═╝╚══════╝

██╗░░██╗███████╗░█████╗░██████╗░███████╗██████╗░
██║░░██║██╔════╝██╔══██╗██╔══██╗██╔════╝██╔══██╗
███████║█████╗░░███████║██║░░██║█████╗░░██████╔╝
██╔══██║██╔══╝░░██╔══██║██║░░██║██╔══╝░░██╔══██╗
██║░░██║███████╗██║░░██║██████╔╝███████╗██║░░██║
╚═╝░░╚═╝╚══════╝╚═╝░░╚═╝╚═════╝░╚══════╝╚═╝░░╚═╝

░█████╗░███╗░░██╗░█████╗░██╗░░░░░██╗░░░██╗███████╗███████╗██████╗░
██╔══██╗████╗░██║██╔══██╗██║░░░░░╚██╗░██╔╝╚════██║██╔════╝██╔══██╗
███████║██╔██╗██║███████║██║░░░░░░╚████╔╝░░░███╔═╝█████╗░░██████╔╝
██╔══██║██║╚████║██╔══██║██║░░░░░░░╚██╔╝░░██╔══╝░░██╔══╝░░██╔══██╗
██║░░██║██║░╚███║██║░░██║███████╗░░░██║░░░███████╗███████╗██║░░██║
╚═╝░░╚═╝╚═╝░░╚══╝╚═╝░░╚═╝╚══════╝░░░╚═╝░░░╚══════╝╚══════╝╚═╝░░╚═╝


The program is a Python script that verifies the DMARC alignment of an email header. It takes an email file as input and checks if the DMARC alignment is valid or invalid based on the presence of the "Authentication-Results" header field in the email and the value of the "dmarc" tag.

Example:
Let's say we have an email file named "example.eml" located in the current directory.
The email has a valid DMARC alignment. We can run the program using the following command:

python email_header_analyzer.py example.eml
