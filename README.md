#include <bits/stdc++.h>
using namespace std;
void geeks()
{
    int var = 20;

    // declare pointer variable
    int* ptr;

    // note that data type of ptr and var must be same
    ptr = &var;

    // assign the address of a variable to a pointer
    cout << "Value at ptr = " << ptr << "\n";
    cout << "Value at var = " << var << "\n";
    cout << "Value at *ptr = " << *ptr << "\n";
}
// Driver program
int main() 
{ 
#include <bits/stdc++.h>
using namespace std;

// Function to recursively remove adjacent duplicates
string rremove(string s) {
    // Create an empty string to build the result
    string sb = ""; 

    // Get the size of the input string
    int n = s.size(); 

    // Iterate over the length of current string
    for (int i = 0; i < n; i++) {
        bool repeated = false;

        // Check if the current characteris the same
        // as the next one
        while (i + 1 < n && s[i] == s[i + 1]) {
            repeated = true;  // Mark as repeated
          
            // Skip the next character
            // since it's a duplicate
            i++;  
        }

        // If the character was not repeated,
        // add it to the result string
        if (!repeated) sb += s[i];
    }

    // If no changes made, return the result string
    if (n == sb.length())
        return sb;
    
    // Otherwise, recursively call the function 
    // to check for more duplicates
    return rremove(sb);
}

int main() {
    string s = "geeksforgeek";  
    string result = rremove(s);  
    cout << result << endl;
    
    return 0;
}
 A patent license is "discriminatory" if it does not include within
the scope of its coverage, prohibits the exercise of, or is
conditioned on the non-exercise of one or more of the rights that are
specifically granted under this License.  You may not convey a covered
work if you are a party to an arrangement with a third party that is
in the business of distributing software, under which you make payment
to the third party based on the extent of your activity of conveying
the work, and under which the third party grants, to any of the
parties who would receive the covered work from you, a discriminatory
patent license (a) in connection with copies of the covered work
conveyed by you (or copies made from those copies), or (b) primarily
for and in connection with specific products or compilations that
contain the covered work, unless you entered into that arrangement,
or that patent license was granted, prior to 28 March 2007.
Bots: Chatbots assist clients to get to the point quickly by answering inquiries and referring them to relevant resources and products at any time of day or night. To be effective, chatbots must be fast, smart, and easy to use, To accomplish this, chatbots employ NLP to understand language, usually over text or voice-recognition interactions
Supporting Invisible UI: Almost every connection we have with machines involves human communication, both spoken and written. Amazon’s Echo is only one illustration of the trend toward putting humans in closer contact with technology in the future. The concept of an invisible or zero user interface will rely on direct communication between the user and the machine, whether by voice, text, or a combination of the two. NLP helps to make this concept a real-world thing.
Smarter Search: NLP’s future also includes improved search, something we’ve been discussing at Expert System for a long time. Smarter search allows a chatbot to understand a customer’s request can enable “search like you talk” functionality (much like you could query Siri) rather than focusing on keywords or topics. Google recently announced that NLP capabilities have been added to Google Drive, allowing users to search for documents and content using natural language.
Future Enhancements: 
Companies like Google are experimenting with Deep Neural Networks (DNNs) to push the limits of NLP and make it possible for human-to-machine interactions to feel just like human-to-human interactions.
Basic words can be further subdivided into proper semantics and used in NLP algorithms.
The NLP algorithms can be used in various languages that are currently unavailable such as regional languages or languages spoken in rural areas etc.
Translation of a sentence in one language to the same sentence in another Language at a broader scope.
Conclusion
In conclusion, the field of Natural Language Processing (NLP) has significantly transformed the way humans interact with machines, enabling more intuitive and efficient communication. NLP encompasses a wide range of techniques and methodologies to understand, interpret, and generate human language. From basic tasks like tokenization and part-of-speech tagging to advanced applications like sentiment analysis and machine translation, the impact of NLP is evident across various domains. As the technology continues to evolve, driven by advancements in machine learning and artificial intelligence, the potential for NLP to enhance human-computer interaction and solve complex language-related challenges remains immense. Understanding the core concepts and applications of Natural Language Processing is crucial for anyone looking to leverage its capabilities in the modern digital landscape.

Natural Language Processing – FAQs
What are NLP models?

NLP models are computational systems that can process natural language data, such as text or speech, and perform various tasks, such as translation, summarization, sentiment analysis, etc. NLP models are usually based on machine learning or deep learning techniques that learn from large amounts of language data.

# Python code to demonstrate variance() 
# function on varying range of data-types

# importing statistics module
from statistics import variance

# importing fractions as parameter values
from fractions import Fraction as fr

# tuple of a set of positive integers
# numbers are spread apart but not very much
sample1 = (1, 2, 5, 4, 8, 9, 12)

# tuple of a set of negative integers
sample2 = (-2, -4, -3, -1, -5, -6)

# tuple of a set of positive and negative numbers
# data-points are spread apart considerably 
sample3 = (-9, -1, -0, 2, 1, 3, 4, 19)

# tuple of a set of fractional numbers
sample4 = (fr(1, 2), fr(2, 3), fr(3, 4),
                     fr(5, 6), fr(7, 8))

# tuple of a set of floating point values
sample5 = (1.23, 1.45, 2.1, 2.2, 1.9)

# Print the variance of each samples
print("Variance of Sample1 is % s " %(variance(sample1)))
print("Variance of Sample2 is % s " %(variance(sample2)))
print("Variance of Sample3 is % s " %(variance(sample3)))
print("Variance of Sample4 is % s " %(variance(sample4)))
print("Variance of Sample5 is % s " %(variance(sample5)))
