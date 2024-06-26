# fuff_cookbook
FFUF (Fuzz Faster U Fool) is a fast and flexible web fuzzing tool used primarily for discovering hidden files, directories, and parameters on web servers. It works by sending a large number of HTTP requests to a target web application and analyzing the responses to identify potential vulnerabilities or hidden resources. Key features include:
Speed: Optimized for high-speed fuzzing, capable of sending thousands of requests per second.
Flexibility: Supports a variety of input methods and formats, allowing customization for different fuzzing scenarios.
Wordlist Management: Utilizes user-provided wordlists to perform brute-force attacks on URLs, parameters, and more.
Customizable Output: Offers multiple output formats, including JSON and HTML, for easy analysis and reporting.
Integration: Can be integrated with other tools and workflows to enhance security testing processes.
FFUF is widely used by security professionals and penetration testers to uncover hidden vulnerabilities and improve the security posture of web applications.

Firstly install ffuf tool on your system by typing :
sudo apt install ffuf -y 

![image](https://github.com/Harryagarwal/fuff_cookbook/assets/86568123/e322b788-f6ff-417c-8052-5a862a5d77c7)


 
Then type ffuf on the terminal to start it:
 ![image](https://github.com/Harryagarwal/fuff_cookbook/assets/86568123/fdd3ffad-ef53-420c-a56b-1c1dafce5405)


Then search the wordlist in kali linux :
/usr/share/wordlists
 ![image](https://github.com/Harryagarwal/fuff_cookbook/assets/86568123/e9e28bd1-347f-4bc3-950b-611c82e6e29a)


taken Metasploit able as an target option to perform the directory busting:
 
![image](https://github.com/Harryagarwal/fuff_cookbook/assets/86568123/df527ebc-ef66-43ae-a4a9-f496b25a4193)

started the fuzzing on metasploitable ip:
 ![image](https://github.com/Harryagarwal/fuff_cookbook/assets/86568123/3d130456-ed3a-4d36-b5df-5df8b5bad947)

here we can see there are several directory found with some the directory with status code of 200,300,400 etc
