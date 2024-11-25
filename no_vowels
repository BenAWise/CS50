// Write a function to replace vowels with numbers
// Get practice with strings
// Get practice with command line
// Get practice with switch

#include <cs50.h>
#include <stdio.h>
#include <string.h>
#include <stdlib.h>

string replace(string input);

int main(int argc, string argv[])
{
    if (argc < 2)
    {
        printf("Usage: ./no-vowels [string to modify ...]\n");
        return 1;
    }

    for (int i = 1; i < argc; i++)
    {
        printf("%s ", replace(argv[i]));
    }
    printf("\n");

}


string replace(string input)
{
    int string_length = strlen(input);
    string leetspeak = malloc((string_length +1) * sizeof(char));

    // This function will change the following vowels to numbers:
    // a becomes 6, e becomes 3, i becomes 1, o becomes 0 and u does not change.

    for (int i = 0; i < string_length; i++)
    {
        switch (input[i])
        {
            case 'a':
            leetspeak[i] = '6';
            break;

            case 'e':
            leetspeak[i] = '3';
            break;

            case 'i':
            leetspeak[i] = '1';
            break;

            case 'o':
            leetspeak[i] = '0';
            break;

            default:
            leetspeak[i] = input[i];
            break;
        }
    }

    return leetspeak;
}
