{
  "nbformat": 4,
  "nbformat_minor": 0,
  "metadata": {
    "colab": {
      "name": "Untitled36.ipynb",
      "provenance": [],
      "include_colab_link": true
    },
    "kernelspec": {
      "name": "python3",
      "display_name": "Python 3"
    }
  },
  "cells": [
    {
      "cell_type": "markdown",
      "metadata": {
        "id": "view-in-github",
        "colab_type": "text"
      },
      "source": [
        "<a href=\"https://colab.research.google.com/github/zxcvbnm884162/CS4High-4080E007/blob/master/MyPython/test.ipynb\" target=\"_parent\"><img src=\"https://colab.research.google.com/assets/colab-badge.svg\" alt=\"Open In Colab\"/></a>"
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "EXqpyoG5qh2i",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 87
        },
        "outputId": "99d98567-c0bb-4f47-bb69-059817a5df30"
      },
      "source": [
        "# 10-1\n",
        "print(\"hello!\") \n",
        "print(3*2*(17-2.1)) \n",
        "print(\"abc\"+\"def\")\n",
        "word = \"art\"\n",
        "print(word.replace(\"r\", \"n\"))"
      ],
      "execution_count": 1,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "hello!\n",
            "89.4\n",
            "abcdef\n",
            "ant\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "tYPrcg43qmsM",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 52
        },
        "outputId": "45b734bd-0fdb-4162-b385-7deeda63d137"
      },
      "source": [
        "# 10-2\n",
        "a= 1\n",
        "b= 2\n",
        "c = a/b\n",
        "print(a, \"/\", b, \"=\", c) \n",
        "add = str(a)+\"/\"+str(b)+\"=\"+str(c)\n",
        "print(add)"
      ],
      "execution_count": 2,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "1 / 2 = 0.5\n",
            "1/2=0.5\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "6vflY7dbqmu7",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 52
        },
        "outputId": "82369360-8b83-4f8a-d3f9-9fc6d8b7778e"
      },
      "source": [
        "# 10-3\n",
        "input(\"Where do you live? \")\n",
        "print(\"I live in Boston. \")"
      ],
      "execution_count": 7,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "Where do you live? 台南市\n",
            "I live in Boston. \n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "ept2svuDqmxj",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 70
        },
        "outputId": "f913c546-bd51-4ec0-e498-9625c89c70e8"
      },
      "source": [
        "# 10-4\n",
        "user_place = input(\"Where do you live? \")\n",
        "text = user_place.capitalize()+ \"!\"\n",
        "print(text) \n",
        "print(\"I hear it's nice there!\") "
      ],
      "execution_count": 8,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "Where do you live? 台南市\n",
            "台南市!\n",
            "I hear it's nice there!\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "yev_Eoj4qm0E",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 70
        },
        "outputId": "dd351133-5392-4982-9507-a46d39c95db1"
      },
      "source": [
        "# 10-5\n",
        "num = int(input (\"Enter a number to find the square of: \"))\n",
        "user_input = input(\"Enter a integer to find the square of: \")\n",
        "num = int(user_input) \n",
        "print(num*num)"
      ],
      "execution_count": 9,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "Enter a number to find the square of: 1\n",
            "Enter a integer to find the square of: 2\n",
            "4\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "FJqGBkFRqqxM",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 70
        },
        "outputId": "93edb84e-007b-48c8-b86b-5051b51aa3ad"
      },
      "source": [
        "# 10-6\n",
        "num1 = float(input(\"Enter a number: \"))\n",
        "num2 = float(input(\"Enter another number: \"))\n",
        "print(num1, \"*\", num2, \"=\", num1*num2)"
      ],
      "execution_count": 10,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "Enter a number: 1\n",
            "Enter another number: 2\n",
            "1.0 * 2.0 = 2.0\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "gdv5kzgEqm2c",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 70
        },
        "outputId": "7af0ae23-1894-43d3-847c-481f54ada397"
      },
      "source": [
        "# 13-1\n",
        "num = int(input(\"Enter a number: \"))\n",
        "if num > 0:\n",
        "    print(\"num is positive\")\n",
        "print(\"finished comparing num to 0\") "
      ],
      "execution_count": 11,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "Enter a number: 1\n",
            "num is positive\n",
            "finished comparing num to 0\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "LqzLpt_-qm4v",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 70
        },
        "outputId": "8e6f23ff-6e7a-47d6-a45a-2a9092e5c1b5"
      },
      "source": [
        "# 13-2\n",
        "num_a = int(input(\"Pick a number: \"))   \n",
        "if num_a > 0:\n",
        "    print(\"Your number is positive\")   \n",
        "if num_a < 0:\n",
        "    print(\"Your number is negative \") \n",
        "if num_a == 0: \n",
        "    print(\"Your number is zero\")\n",
        "print(\"Finished!\")"
      ],
      "execution_count": 13,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "Pick a number: 0\n",
            "Your number is zero\n",
            "Finished!\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "PysQ1bqsqm9T",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 70
        },
        "outputId": "a48b0025-009f-4818-a9fe-dff4c0ef5ca1"
      },
      "source": [
        "# 13-3巢狀條件式\n",
        "num_a = int(input(\"Number? \"))\n",
        "num_b = int(input(\"Number? \"))\n",
        "if num_a < 0:      \n",
        "    print(\"num_a is negative\")\n",
        "    if num_b < 0:\n",
        "        print(\"num_b is negative\")\n",
        "print(\"Finished\")"
      ],
      "execution_count": 17,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "Number? 2\n",
            "Number? 2\n",
            "Finished\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "0iKnPQf8qm7G",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 70
        },
        "outputId": "ac0f8305-3046-49ec-f8f7-c5dbbe31d77d"
      },
      "source": [
        "# 13-3非巢狀條件式\n",
        "num_a = int(input(\"Number? \"))\n",
        "num_b = int(input(\"Number? \"))\n",
        "if num_a < 0:\n",
        "   print(\"num_a is negative\") \n",
        "if num_b < 0:\n",
        "    print(\"num_b is negative\")\n",
        "print(\"Finished\")"
      ],
      "execution_count": 16,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "Number? 2\n",
            "Number? 2\n",
            "Finished\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "Jl9U9_k9qnB3",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 70
        },
        "outputId": "e4de5cfe-94d4-41c7-cd21-ea4ce8d5ccaa"
      },
      "source": [
        "# 13-4\n",
        "price = float(input(\"How much does a chocolate bar cost? \"))\n",
        "hungry = input(\"Are you hungry(yes or no)? \")\n",
        "\n",
        "bars = 0\n",
        "if hungry == \"yes\": \n",
        "    if price < 10:\n",
        "        print(\"Buy all chocolate bars.\")\n",
        "        bar = 100\n",
        "    if 10 <= price <= 50:\n",
        "        print(\"Buy 10 chocolate bars.\")     \n",
        "        bars = 10\n",
        "    if price > 50:\n",
        "        print(\"Buy only one chocolate bar.\")\n",
        "        bars = 1\n",
        "if hungry == \"no\":\n",
        "    print(\"Stick to the shopping list.\")\n",
        "if bars > 10:\n",
        "    print(\"Cashier says: someone's hungry!\")"
      ],
      "execution_count": 19,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "How much does a chocolate bar cost? 40\n",
            "Are you hungry(yes or no)? yes\n",
            "Buy 10 chocolate bars.\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "kT2AmRkVrq9U",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 70
        },
        "outputId": "fedd5a4f-97fe-4369-c662-81c7482725d0"
      },
      "source": [
        "# 13-5\n",
        "num_a = int(input(\"pick a number:\"))\n",
        "num_b = int(input(\"pick a number:\"))\n",
        "if num_a < 0 and num_b < 0: \n",
        "    print(\"both negative\")"
      ],
      "execution_count": 23,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "pick a number:-1\n",
            "pick a number:-2\n",
            "both negative\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "KxtbApsMrq_s",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 52
        },
        "outputId": "62ea2f76-c164-47f3-bfbd-2ced0d5b1217"
      },
      "source": [
        "# 14-1\n",
        "Num=int(input(\"please pick a number: \"))\n",
        "if Num%2==0:\n",
        "    print(\"Even Number\")\n",
        "else:\n",
        "    print(\"Odd Number\")"
      ],
      "execution_count": 26,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "please pick a number: 400\n",
            "Even Number\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "GthYL3iWrrBk",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 52
        },
        "outputId": "d53bd256-3bfa-4cc4-bcba-e5f135a0b716"
      },
      "source": [
        "# 14-2\n",
        "num = int(input(\"Enter a number: \"))\n",
        "if num > 0:\n",
        "    print(\"num is positive\")\n",
        "elif num < 0:\n",
        "    print(\"num is negative\")\n",
        "else:\n",
        "    print(\"num is zero\")"
      ],
      "execution_count": 25,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "Enter a number: 20\n",
            "num is positive\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "_C4veUFnr_w9",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 87
        },
        "outputId": "9dffdbf8-b66b-4ca6-e604-2d3b8f7d0a11"
      },
      "source": [
        "# 14-3\n",
        "num_a = int(input(\"pick a number: \"))\n",
        "num_b = int(input(\"pick another number: \"))\n",
        "lucky_num = 7\n",
        "if num_a==num_b:\n",
        "    print(\"You enter the same number\")\n",
        "else:\n",
        "    if num_a > 0 and num_b > 0:\n",
        "        print(\"both numbers are positive\")\n",
        "    elif num_a < 0 and num_b < 0:\n",
        "        print(\"both numbers are negative\")\n",
        "    else:\n",
        "        print(\"numbers have opposite sign\")\n",
        "if num_a == lucky_num or num_b == lucky_num:\n",
        "    print(\"you also guessed my lucky number!\")\n",
        "else:\n",
        "    print(\"I have a secret number in mind...\")"
      ],
      "execution_count": 29,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "pick a number: -1\n",
            "pick another number: 2\n",
            "numbers have opposite sign\n",
            "I have a secret number in mind...\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "a8nXAD-Jr_51",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 87
        },
        "outputId": "31079ac2-4030-45fd-f7eb-87aed42bc0e5"
      },
      "source": [
        "# 14-4\n",
        "num_a = int(input(\"pick a number: \"))\n",
        "num_b = int(input(\"pick another number: \"))\n",
        "lucky_num = 7\n",
        "if num_a == num_b:\n",
        "    print(\"You enter the same number\")\n",
        "elif num_a > 0 and num_b > 0:\n",
        "    print(\"both numbers are positive\")\n",
        "elif num_a < 0 and num_b < 0:\n",
        "    print(\"both numbers are negative\")\n",
        "else:\n",
        "    print(\"numbers have opposite sign\")\n",
        "if num_a == lucky_num or num_b == lucky_num:\n",
        "    print(\"you also guessed my lucky number!\")\n",
        "else:\n",
        "    print(\"I have a secret number in mind...\")"
      ],
      "execution_count": 30,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "pick a number: -2\n",
            "pick another number: 5\n",
            "numbers have opposite sign\n",
            "I have a secret number in mind...\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "WEfuj2qxr_8U",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 87
        },
        "outputId": "5a1f18c9-41c4-4360-f1f6-cd727d552dca"
      },
      "source": [
        "# 14-5\n",
        "greeting = input(\"Say hi in English or Spanish! \")\n",
        "greet_en =(\"hi\", \"Hi\", \"hello\", \"Hello\")\n",
        "greet_sp =(\"hola\", \"Hola\")\n",
        "if greeting not in greet_en and greeting not in greet_sp:\n",
        "    print(\"I don't understand your greeting.\")\n",
        "elif greeting in greet_en:\n",
        "  num = int(input(\"Enter 1 or 2: \"))\n",
        "  print(\"You speak English!\")\n",
        "  if num == 1:\n",
        "      print(\"one\")\n",
        "  elif num == 2:\n",
        "      print(\"two\")\n",
        "elif greeting in greet_sp:\n",
        "    num = int(input(\"Enter 1 or 2: \"))\n",
        "    print(\"You speak Spanish!\")\n",
        "    if num == 1:\n",
        "        print(\"uno\")\n",
        "    elif num == 2:\n",
        "        print(\"dos\")"
      ],
      "execution_count": 33,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "Say hi in English or Spanish! Hello\n",
            "Enter 1 or 2: 1\n",
            "You speak English!\n",
            "one\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "i6-hpTIXr_-n",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 105
        },
        "outputId": "faa4c337-1324-4a9d-ed0d-d1e95aba8ac3"
      },
      "source": [
        "# 15-1\n",
        "print(\"Hello World!.\")\n",
        "print(\"My name is LEO!\")\n",
        "print(\"I like eat noodles.\")\n",
        "print(\"I like baseketball\")\n",
        "print(\"Nice to meet you...\")"
      ],
      "execution_count": 35,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "Hello World!.\n",
            "My name is LEO!\n",
            "I like eat noodles.\n",
            "I like baseketball\n",
            "Nice to meet you...\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "2BJl1iZxtedl",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 141
        },
        "outputId": "e02cdf26-ec52-4709-efc7-71bfec101cd5"
      },
      "source": [
        "# 15-2\n",
        "do = input(\":: \")\n",
        "if do == \"LOOK\":   \n",
        "    print(\"You are stuck in a sand ditch.\")\n",
        "    print(\"Crawl out LEFT or RIGHT.\")\n",
        "    do = input(\":: \")\n",
        "    if do == \"LEFT\":   \n",
        "        print(\"You make it out and see a ship!\")\n",
        "        print(\"You survived!\")\n",
        "    elif do == \"RIGHT\":   \n",
        "        print(\"No can do. That side is very slippery.\")\n",
        "    print(\"You fall very far into some weird cavern.\")\n",
        "    print(\"You do not survive :(\")\n",
        "else:\n",
        "    print(\"You can only do actions shown in capital letters.\")\n",
        "    print(\"Try again!\")"
      ],
      "execution_count": 36,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            ":: LOOK\n",
            "You are stuck in a sand ditch.\n",
            "Crawl out LEFT or RIGHT.\n",
            ":: RIGHT\n",
            "No can do. That side is very slippery.\n",
            "You fall very far into some weird cavern.\n",
            "You do not survive :(\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "6t7fWBurtekU",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 158
        },
        "outputId": "14ba9602-0b3a-4461-a71a-3e38a7453eae"
      },
      "source": [
        "# 15-3\n",
        "print(\"You are on a deserted island in a 2D world.\")\n",
        "print(\"Try to survive until rescue arrives!\")\n",
        "print(\"Available commands are in CAPITAL letters.\")\n",
        "print(\"Any other command exits the program\")\n",
        "print(\"First LOOK around...\")\n",
        "do = input(\":: \")\n",
        "if do == \"LOOK\":\n",
        "    print(\"You are stuck in a sand ditch.\")\n",
        "    print(\"Crawl out LEFT or RIGHT.\")\n",
        "    do = input(\":: \")\n",
        "    if do == \"LEFT\":   \n",
        "        print(\"You see a STARFISH and a CRAB on the sand.\")\n",
        "        print(\"And you're hungry! Which do you eat?\")\n",
        "        do = input(\":: \")\n",
        "        if do==\"STARFISH\":\n",
        "            print(\"Oh no! You immediately don't feel well.\")\n",
        "            print(\"You do not survive :(\")\n",
        "        elif do == \"CRAB\":\n",
        "            print(\"Raw crab should be fine, right? YES or NO.\")\n",
        "            do = input(\":: \")\n",
        "            if do == \"YES\":   \n",
        "                print(\"Ok, You eat it raw. Fingers crossed.\")\n",
        "                print(\"Food in your belly helps you see a TREE.\")\n",
        "                do = input(\":: \")\n",
        "                if do == \"TREE\":   \n",
        "                    print(\"It's a coconut tree! And you're thirsty!\")\n",
        "                    print(\"Do you drink the coconut water? YES or NO.\")\n",
        "                    do = input(\":: \")\n",
        "                    if do == \"YES\": \n",
        "                        print(\"Oh boy. Coconut water and raw crab don't mix.\")\n",
        "                        print(\"You do not survive :(\")\n",
        "                elif do == \"NO\":\n",
        "                    print(\"Good choice.\")\n",
        "                    print(\"Look! It's a rescue plane! Youmade it! \\o/\")\n",
        "            elif do == \"NO\": \n",
        "                print(\"Well, there's nothing else left to eat.\")\n",
        "                print(\"You do not survive :(\")\n",
        "    elif do == \"RIGHT\":   \n",
        "        print(\"No can do. That side is very slippery.\")\n",
        "        print(\"You fall very far into some weird cavern.\")\n",
        "        print(\"You do not survive :(\")\n",
        "else:\n",
        "    print(\"You can only do actions shown in capital letters.\")\n",
        "    print(\"Try again!\")"
      ],
      "execution_count": 38,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "You are on a deserted island in a 2D world.\n",
            "Try to survive until rescue arrives!\n",
            "Available commands are in CAPITAL letters.\n",
            "Any other command exits the program\n",
            "First LOOK around...\n",
            ":: \n",
            "You can only do actions shown in capital letters.\n",
            "Try again!\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "DdshjfdFtem1",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 141
        },
        "outputId": "c66c231a-0867-49c9-d5ec-82cb21436fc6"
      },
      "source": [
        "# 16-1\n",
        "s = input(\" 請輸入顯示內容 : \")\n",
        "n = int(input(\" 請輸入顯示次數 : \"))\n",
        " \n",
        "while n > 0:    \n",
        "    print(s)\n",
        "\n",
        "    n = n-1"
      ],
      "execution_count": 46,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            " 請輸入顯示內容 : 請您在輸入一次!\n",
            " 請輸入顯示次數 : 5\n",
            "請您在輸入一次!\n",
            "請您在輸入一次!\n",
            "請您在輸入一次!\n",
            "請您在輸入一次!\n",
            "請您在輸入一次!\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "5tVWCYQVtepJ",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 123
        },
        "outputId": "00aa19d6-3d18-49c9-996d-6ba3eb37fdce"
      },
      "source": [
        "# 16-2\n",
        "lucky_num = 77\n",
        "guess = int(input(\"Guess a Number(0-99): \"))\n",
        "tries = 1\n",
        "while guess != lucky_num:\n",
        "    print(\"You tried to guess\", tries, \"times\")\n",
        "    guess = int(input(\"Guess again: \"))\n",
        "    tries += 1\n",
        "print(\"You got it!\")"
      ],
      "execution_count": 47,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "Guess a Number(0-99): 55\n",
            "You tried to guess 1 times\n",
            "Guess again: 45\n",
            "You tried to guess 2 times\n",
            "Guess again: 77\n",
            "You got it!\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "FzNn_1zNtesl",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 52
        },
        "outputId": "35f0613d-f7dc-4db8-f970-719980280db6"
      },
      "source": [
        "# 16-3\n",
        "secret = \"code\"\n",
        "max_tries = 100\n",
        "guess = input(\"Guess a word: \")\n",
        "tries = 1\n",
        "while guess != secret:\n",
        "    print(\"You tried to guess\", tries, \"times\")\n",
        "    if tries == max_tries:\n",
        "        print(\"You ran out of tries.\")\n",
        "        break\n",
        "    guess = input(\"Guess again: \")\n",
        "    tries += 1\n",
        "if tries <= max_tries and guess == secret:\n",
        "    print(\"You got it!\")"
      ],
      "execution_count": 49,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "Guess a word: code\n",
            "You got it!\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "baQisQpSteu7",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 34
        },
        "outputId": "8a21c99e-804c-475b-ac95-47fd8a5ac145"
      },
      "source": [
        "# 16-4\n",
        "i= 1\n",
        "while(i < 18):\n",
        "    if i == 5:\n",
        "        i += 1\n",
        "        continue\n",
        "    print(i, end=' ')\n",
        "    i += 1\n",
        "print(\"End\")"
      ],
      "execution_count": 52,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "1 2 3 4 6 7 8 9 10 11 12 13 14 15 16 17 End\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "ZpPx5qm4tewl",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 123
        },
        "outputId": "7fa10e35-aa11-434d-9edb-b2430e2a0295"
      },
      "source": [
        "# 16-5\n",
        "#s = \"\" \n",
        "while s != \"喵喵\":\n",
        "    if s != \"\":\n",
        "        print(\" 不對喔!\")\n",
        "    s = input(\" 請輸入通關密語:\")\n",
        "    if s == \"out\":\n",
        "        break\n",
        "else: \n",
        "    print(\" 恭喜你過關了 \")\n",
        "print(\" 再見!\")"
      ],
      "execution_count": 53,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            " 不對喔!\n",
            " 請輸入通關密語:喵\n",
            " 不對喔!\n",
            " 請輸入通關密語:喵喵\n",
            " 恭喜你過關了 \n",
            " 再見!\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "DkM4hSOhvDuW",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 230
        },
        "outputId": "ed1e74a3-02eb-4e69-ccef-dd7473c4589d"
      },
      "source": [
        "# 17-1不使用迴圈\n",
        "print(\"\\tHello Python\") ; print(\"\\t**************\")\n",
        "print(\"\\tHello Python\") ; print(\"\\t**************\")\n",
        "print(\"\\tHello Python\") ; print(\"\\t**************\")\n",
        "print(\"\\tHello Python\") ; print(\"\\t**************\")\n",
        "print(\"\\tHello Python\") ; print(\"\\t**************\")\n",
        "print(\"\\tHello Python\") ; print(\"\\t**************\")"
      ],
      "execution_count": 65,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "\tHello Python\n",
            "\t**************\n",
            "\tHello Python\n",
            "\t**************\n",
            "\tHello Python\n",
            "\t**************\n",
            "\tHello Python\n",
            "\t**************\n",
            "\tHello Python\n",
            "\t**************\n",
            "\tHello Python\n",
            "\t**************\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "UI2GCHflvDwr",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 194
        },
        "outputId": "17cd22a5-68f1-47dd-97df-d49e6fd30b03"
      },
      "source": [
        "# 17-2使用for迴圈\n",
        "for i in range(5):\n",
        "    print(\"Hello Python\") ; print(\"************\")"
      ],
      "execution_count": 70,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "Hello Python\n",
            "************\n",
            "Hello Python\n",
            "************\n",
            "Hello Python\n",
            "************\n",
            "Hello Python\n",
            "************\n",
            "Hello Python\n",
            "************\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "U9nMcHifvDy_",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 52
        },
        "outputId": "b93d5279-99aa-4dc1-bb0e-3d721b7d648f"
      },
      "source": [
        "# 17-3\n",
        "for i in range(10, 1, -2):\n",
        "    print(i, end=\" \")\n",
        "print()\n",
        "for i in range(0, 15, 2): \n",
        "    print(i, end=\" \") "
      ],
      "execution_count": 72,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "10 8 6 4 2 \n",
            "0 2 4 6 8 10 12 14 "
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "1SdapVREvD1M",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 1000
        },
        "outputId": "c65b6949-9ea7-4c96-b6ec-0b36c5e29644"
      },
      "source": [
        "# 17-4\n",
        "for i in range(1, 10):\n",
        "    for j in range(1, 10):\n",
        "        print(j,\"x\",i,\"=\",j*i,end=' ') ; print(\"\\t\")\n",
        "    print()"
      ],
      "execution_count": 88,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "1 x 1 = 1 \t\n",
            "2 x 1 = 2 \t\n",
            "3 x 1 = 3 \t\n",
            "4 x 1 = 4 \t\n",
            "5 x 1 = 5 \t\n",
            "6 x 1 = 6 \t\n",
            "7 x 1 = 7 \t\n",
            "8 x 1 = 8 \t\n",
            "9 x 1 = 9 \t\n",
            "\n",
            "1 x 2 = 2 \t\n",
            "2 x 2 = 4 \t\n",
            "3 x 2 = 6 \t\n",
            "4 x 2 = 8 \t\n",
            "5 x 2 = 10 \t\n",
            "6 x 2 = 12 \t\n",
            "7 x 2 = 14 \t\n",
            "8 x 2 = 16 \t\n",
            "9 x 2 = 18 \t\n",
            "\n",
            "1 x 3 = 3 \t\n",
            "2 x 3 = 6 \t\n",
            "3 x 3 = 9 \t\n",
            "4 x 3 = 12 \t\n",
            "5 x 3 = 15 \t\n",
            "6 x 3 = 18 \t\n",
            "7 x 3 = 21 \t\n",
            "8 x 3 = 24 \t\n",
            "9 x 3 = 27 \t\n",
            "\n",
            "1 x 4 = 4 \t\n",
            "2 x 4 = 8 \t\n",
            "3 x 4 = 12 \t\n",
            "4 x 4 = 16 \t\n",
            "5 x 4 = 20 \t\n",
            "6 x 4 = 24 \t\n",
            "7 x 4 = 28 \t\n",
            "8 x 4 = 32 \t\n",
            "9 x 4 = 36 \t\n",
            "\n",
            "1 x 5 = 5 \t\n",
            "2 x 5 = 10 \t\n",
            "3 x 5 = 15 \t\n",
            "4 x 5 = 20 \t\n",
            "5 x 5 = 25 \t\n",
            "6 x 5 = 30 \t\n",
            "7 x 5 = 35 \t\n",
            "8 x 5 = 40 \t\n",
            "9 x 5 = 45 \t\n",
            "\n",
            "1 x 6 = 6 \t\n",
            "2 x 6 = 12 \t\n",
            "3 x 6 = 18 \t\n",
            "4 x 6 = 24 \t\n",
            "5 x 6 = 30 \t\n",
            "6 x 6 = 36 \t\n",
            "7 x 6 = 42 \t\n",
            "8 x 6 = 48 \t\n",
            "9 x 6 = 54 \t\n",
            "\n",
            "1 x 7 = 7 \t\n",
            "2 x 7 = 14 \t\n",
            "3 x 7 = 21 \t\n",
            "4 x 7 = 28 \t\n",
            "5 x 7 = 35 \t\n",
            "6 x 7 = 42 \t\n",
            "7 x 7 = 49 \t\n",
            "8 x 7 = 56 \t\n",
            "9 x 7 = 63 \t\n",
            "\n",
            "1 x 8 = 8 \t\n",
            "2 x 8 = 16 \t\n",
            "3 x 8 = 24 \t\n",
            "4 x 8 = 32 \t\n",
            "5 x 8 = 40 \t\n",
            "6 x 8 = 48 \t\n",
            "7 x 8 = 56 \t\n",
            "8 x 8 = 64 \t\n",
            "9 x 8 = 72 \t\n",
            "\n",
            "1 x 9 = 9 \t\n",
            "2 x 9 = 18 \t\n",
            "3 x 9 = 27 \t\n",
            "4 x 9 = 36 \t\n",
            "5 x 9 = 45 \t\n",
            "6 x 9 = 54 \t\n",
            "7 x 9 = 63 \t\n",
            "8 x 9 = 72 \t\n",
            "9 x 9 = 81 \t\n",
            "\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "sFyyKLpJvD3o",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 34
        },
        "outputId": "38091ca5-4166-462f-9859-072afadf57c0"
      },
      "source": [
        "# 17-5\n",
        "for i in range(1, 21):\n",
        "    if i == 5:\n",
        "        continue\n",
        "    print(i, end=\" \")\n",
        "    if i == 20:\n",
        "        break\n",
        "print(\"END\")"
      ],
      "execution_count": 91,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "1 2 3 4 6 7 8 9 10 11 12 13 14 15 16 17 18 19 20 END\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "wk5Ft0_fvD5n",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 141
        },
        "outputId": "d32b6d78-3b42-46b6-cb4c-127d0be53135"
      },
      "source": [
        "# 17-6\n",
        "num = int(input(\"Please specify the range(0~N): \"))\n",
        "for i in range(2, num+1):   \n",
        "    for j in range(2, i):\n",
        "        if(i%j == 0): \n",
        "            break \n",
        "    else: \n",
        "        print(i)"
      ],
      "execution_count": 93,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "Please specify the range(0~N): 15\n",
            "2\n",
            "3\n",
            "5\n",
            "7\n",
            "11\n",
            "13\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "RD_RBQCvvD7y",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 70
        },
        "outputId": "7e60b73f-3e3d-4ee1-b739-a8295e2a4e5e"
      },
      "source": [
        "# 18-1\n",
        "for ch in \"蔡德龍\":\n",
        "    print(\"the character is\", ch) "
      ],
      "execution_count": 96,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "the character is 蔡\n",
            "the character is 德\n",
            "the character is 龍\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "9mhrJz2zvD9_",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 70
        },
        "outputId": "1fc6e7cf-0ebc-4264-81a1-28f2e084cd99"
      },
      "source": [
        "# 18-2\n",
        "my_string = \"蔡德龍\"\n",
        "len_s = len(my_string)\n",
        "for i in range(len_s):\n",
        "    print(\"the character is\", my_string[i]) "
      ],
      "execution_count": 99,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "the character is 蔡\n",
            "the character is 德\n",
            "the character is 龍\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "SniQAuZHx2LA",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 87
        },
        "outputId": "842e650d-900b-4732-a30a-523c76efc923"
      },
      "source": [
        "# 18-3\n",
        "winners =(\"Peter\", \"Mark\", \"Joy\")\n",
        "print(\" 恭喜以下得獎人:\")\n",
        "for name in winners:\n",
        "    print(name)"
      ],
      "execution_count": 100,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            " 恭喜以下得獎人:\n",
            "Peter\n",
            "Mark\n",
            "Joy\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "guqJTfzLx2Nc",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 87
        },
        "outputId": "0e0b68dc-f553-4d03-9daa-c04a44461179"
      },
      "source": [
        "# 18-4\n",
        "prizes =(\" 頭獎 \", \" 二獎 \", \" 三獎 \")\n",
        "winners =(\"Peter\", \"Mark\", \"Joy\")\n",
        "print(\" 恭喜以下得獎人:\")\n",
        "for i in range(3):\n",
        "    print(prizes[i]+ \":\" + winners[i]) "
      ],
      "execution_count": 101,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            " 恭喜以下得獎人:\n",
            " 頭獎 :Peter\n",
            " 二獎 :Mark\n",
            " 三獎 :Joy\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "vYPZSLfRx2P4",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 87
        },
        "outputId": "25527ad5-7d57-4379-b50b-9a109202de3b"
      },
      "source": [
        "# 18-5\n",
        "winners =((\" 頭獎 \", \"Peter\"),(\" 二獎 \", \"Mark\"),(\" 三獎 \", \"Joy\"))\n",
        "print(\" 恭喜以下得獎人:\")\n",
        "for e in winners: \n",
        "    print(e[0]+ \":\" + e[1])"
      ],
      "execution_count": 102,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            " 恭喜以下得獎人:\n",
            " 頭獎 :Peter\n",
            " 二獎 :Mark\n",
            " 三獎 :Joy\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "t2jFW9alx2SN",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 87
        },
        "outputId": "c5450462-a964-435a-cb4e-335e4d373eb7"
      },
      "source": [
        "# 18-6\n",
        "winners =((\" 頭獎 \", \"Peter\"),(\" 二獎 \", \"Mark\"),(\" 三獎 \", \"Joy\"))\n",
        "print(\" 恭喜以下獎人:\")\n",
        "for prize, winner in winners:\n",
        "    print(prize+ \":\" + winner) "
      ],
      "execution_count": 103,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            " 恭喜以下獎人:\n",
            " 頭獎 :Peter\n",
            " 二獎 :Mark\n",
            " 三獎 :Joy\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "aB4S1SlYx2Wy",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 70
        },
        "outputId": "b762b431-96da-46c6-ebfc-0d42d95cc691"
      },
      "source": [
        "# 18-7for迴圈\n",
        "for x in range(3):\n",
        "    print(\"var x is\", x)"
      ],
      "execution_count": 104,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "var x is 0\n",
            "var x is 1\n",
            "var x is 2\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "bEovyn4xx2Ux",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 70
        },
        "outputId": "1a32be40-c7c3-4a75-8d53-31bcfd8904e6"
      },
      "source": [
        "# 18-7while迴圈\n",
        " x = 0\n",
        "while x < 3:\n",
        "    print(\"var x is\", x)\n",
        "    x += 1"
      ],
      "execution_count": 105,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "var x is 0\n",
            "var x is 1\n",
            "var x is 2\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "ioQu_1ewyGB9",
        "colab_type": "code",
        "colab": {}
      },
      "source": [
        "# 19-1\n",
        "words = \"\"\"art\n",
        "hue\n",
        "ink\n",
        "...\n",
        "crosshatching\n",
        "\"\"\"\n",
        "tiles = \"hijklmnop\"\n",
        "all_valid_words =()\n",
        "start = 0\n",
        "end = 0\n",
        "found_words =()   "
      ],
      "execution_count": 0,
      "outputs": []
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "QbJxdBvayFxB",
        "colab_type": "code",
        "colab": {}
      },
      "source": [
        "# 19-2\n",
        "words = \"\"\"art hue\n",
        "ink\n",
        "...\n",
        "crosshatching\n",
        "\"\"\"\n",
        "tiles = \"hijklmnop\"\n",
        "all_valid_words =()\n",
        "start = 0\n",
        "end = 0\n",
        "found_words =() \n",
        "\n",
        "for char in words:\n",
        "    if char == \"\\n\":\n",
        "        all_valid_words = all_valid_words +(words[start:end], )\n",
        "        start = end + 1\n",
        "        end = end +1\n",
        "    else:\n",
        "        end = end + 1 "
      ],
      "execution_count": 0,
      "outputs": []
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "EqL1xqjCyOId",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 34
        },
        "outputId": "240269a0-43d3-4e66-b64b-070c677c02e5"
      },
      "source": [
        "# 19-3\n",
        "words = \"\"\"art hue\n",
        "ink\n",
        "...\n",
        "crosshatching\n",
        "\"\"\"\n",
        "tiles = \"hijklmnop\"\n",
        "all_valid_words =()\n",
        "start = 0\n",
        "end = 0\n",
        "found_words =() \n",
        "\n",
        "for char in words:\n",
        "    if char == \"\\n\":\n",
        "        all_valid_words = all_valid_words +(words[start:end], )\n",
        "        start = end + 1\n",
        "        end = end +1\n",
        "    else:\n",
        "        end = end + 1\n",
        "\n",
        "for word in all_valid_words:\n",
        "    tiles_left = tiles\n",
        "for letter in word:\n",
        "    if letter not in tiles_left:\n",
        "        break\n",
        "    else:\n",
        "        index = tiles_left.find(letter)\n",
        "        tiles_left = tiles_left[:index]+tiles_left[index+1:]\n",
        "    if len(word)== len(tiles)-len(tiles_left):\n",
        "        found_words = found_words +(word, )\n",
        "print(found_words)"
      ],
      "execution_count": 111,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "()\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "zJelopdHyFze",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 87
        },
        "outputId": "18524e81-4863-4c70-bab7-1e30f7f46514"
      },
      "source": [
        "# 20-1\n",
        "a= 2\n",
        "b= 2\n",
        "print(a+b)\n",
        "print(a-b)\n",
        "print(a*b)\n",
        "print(a/b)"
      ],
      "execution_count": 113,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "4\n",
            "0\n",
            "4\n",
            "1.0\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "mevOLV1YyU2v",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 230
        },
        "outputId": "aa83b680-e975-4725-abfc-e3669e0ba2ce"
      },
      "source": [
        "# 20-2\n",
        "a= 2\n",
        "b= 2\n",
        "print(a+b)\n",
        "print(a-b)\n",
        "print(a*b)\n",
        "print(a/b)\n",
        "a= 4\n",
        "b= 4\n",
        "print(a+b)\n",
        "print(a-b)\n",
        "print(a*b)\n",
        "print(a/b)\n",
        "a= 6\n",
        "b= 6\n",
        "print(a+b)\n",
        "print(a-b)\n",
        "print(a*b)\n",
        "print(a/b)"
      ],
      "execution_count": 115,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "4\n",
            "0\n",
            "4\n",
            "1.0\n",
            "8\n",
            "0\n",
            "16\n",
            "1.0\n",
            "12\n",
            "0\n",
            "36\n",
            "1.0\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "nc5bnSAWyF2D",
        "colab_type": "code",
        "colab": {}
      },
      "source": [
        "# 21-1\n",
        "def take_attendance(classroom, who_is_here):\n",
        "    \"\"\"\n",
        "    classroom, tuple\n",
        "    who_is_here, tuple\n",
        "    Checks if every item in classroom is in who_is_here\n",
        "    And prints their name if so.\n",
        "    Returns \"finished taking attendance\"\n",
        "    \"\"\"\n",
        "    for kid in classroom:\n",
        "        if kid in who_is_here:\n",
        "            print(kid)   \n",
        "    return \"finished taking attendance\""
      ],
      "execution_count": 0,
      "outputs": []
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "0S5YwIJuyF4v",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 52
        },
        "outputId": "545b030b-6eb7-46a1-8bd0-911eef42c82f"
      },
      "source": [
        "# 21-2\n",
        "def hello():\n",
        "    print('Hello!')\n",
        "\n",
        "hello()\n",
        "def sayHi(name, title):\n",
        "    print(name + title +' 你好!')\n",
        "sayHi(' 蔡德龍 ', ' 同學 ')"
      ],
      "execution_count": 120,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "Hello!\n",
            " 蔡德龍  同學  你好!\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "H9-fz9V7yF63",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 135
        },
        "outputId": "b641b396-79bc-4304-e4d3-ee379e7be452"
      },
      "source": [
        "# 21-3\n",
        "sayHi(' 王小明 ', title=' 同學 ')\n",
        "sayHi(title=' 同學 ', name=' 王小明 ')\n",
        "sayHi(title=' 同學 ', ' 王小明 ')"
      ],
      "execution_count": 125,
      "outputs": [
        {
          "output_type": "error",
          "ename": "SyntaxError",
          "evalue": "ignored",
          "traceback": [
            "\u001b[0;36m  File \u001b[0;32m\"<ipython-input-125-daa87317dde0>\"\u001b[0;36m, line \u001b[0;32m3\u001b[0m\n\u001b[0;31m    sayHi(title=' 同學 ', ' 王小明 ')\u001b[0m\n\u001b[0m                           ^\u001b[0m\n\u001b[0;31mSyntaxError\u001b[0m\u001b[0;31m:\u001b[0m positional argument follows keyword argument\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "7Nfjia7dyF9F",
        "colab_type": "code",
        "colab": {}
      },
      "source": [
        "# 21-4\n",
        "def get_word_length(word1, word2): \n",
        "    word = word1+word2  \n",
        "    return len(word) \n",
        "    print(\"this never gets printed\") "
      ],
      "execution_count": 0,
      "outputs": []
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "DKvVr1xwyxFK",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 70
        },
        "outputId": "c52fb0a8-f841-4830-aa46-ac93f34c13cc"
      },
      "source": [
        "# 21-5\n",
        "def word_length(word1, word2):\n",
        "    word = word1+word2\n",
        "    return len(word)\n",
        "    print(\"this never gets printed\")\n",
        "    \n",
        "length1 = word_length(\"Rob\", \"Banks\")\n",
        "length2 = word_length(\"Barbie\", \"Kenn\")\n",
        "length3 = word_length(\"Holly\", \"Jolley\")\n",
        "\n",
        "print(\"One name is\", length1, \"letters long.\")\n",
        "print(\"Another name is\", length2, \"letters long.\")\n",
        "print(\"The final name is\", length3, \"letters long.\")"
      ],
      "execution_count": 127,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "One name is 8 letters long.\n",
            "Another name is 10 letters long.\n",
            "The final name is 11 letters long.\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "BQMJApM7yzTm",
        "colab_type": "code",
        "colab": {}
      },
      "source": [
        "# 21-6\n",
        "def add_sub(n1, n2):\n",
        "    add = n1 + n2\n",
        "    sub = n1 - n2\n",
        "    return(add, sub)\n",
        "(a, b)= add_sub(3, 4)"
      ],
      "execution_count": 0,
      "outputs": []
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "3pB7zHJ6yF_U",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 87
        },
        "outputId": "251c4fd3-d8c2-4068-a482-125b0877fdfa"
      },
      "source": [
        "# 21-7\n",
        "def say_name(kid):\n",
        "    print(kid)\n",
        "def show_kid(kid):\n",
        "    return kid\n",
        "say_name(\"Dora\")\n",
        "show_kid(\"Ellie\")\n",
        "print(say_name(\"Frank\"))\n",
        "print(show_kid(\"Gus\"))"
      ],
      "execution_count": 129,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "Dora\n",
            "Frank\n",
            "None\n",
            "Gus\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "QgHCRKQ3y4Fh",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 158
        },
        "outputId": "80298115-0398-4c69-ee24-57e64af1606d"
      },
      "source": [
        "# 21-8\n",
        "def take_attendance(classroom, who_is_here):\n",
        "    \"\"\"\n",
        "    classroom, tuple of strings\n",
        "    who_is_here, tuple of strings\n",
        "    Prints the names of all kids in class who are also in who_is_here\n",
        "    Returns a string, \"finished taking attendance\"\n",
        "    \"\"\"\n",
        "    for kid in classroom:\n",
        "        if kid in who_is_here:\n",
        "            print(kid)\n",
        "    return \"finished taking attendance\"\n",
        "help(take_attendance)"
      ],
      "execution_count": 130,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "Help on function take_attendance in module __main__:\n",
            "\n",
            "take_attendance(classroom, who_is_here)\n",
            "    classroom, tuple of strings\n",
            "    who_is_here, tuple of strings\n",
            "    Prints the names of all kids in class who are also in who_is_here\n",
            "    Returns a string, \"finished taking attendance\"\n",
            "\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "RrJf2SQFy4ID",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 52
        },
        "outputId": "95f5343c-16c8-4b46-a2a1-0e46761ed01a"
      },
      "source": [
        "# 22-1\n",
        "def fairy_tale():   \n",
        "    peter = 5\n",
        "    print(peter)   \n",
        "peter = 30\n",
        "fairy_tale()\n",
        "print(peter)"
      ],
      "execution_count": 131,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "5\n",
            "30\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "memFS-5Ay4KH",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 34
        },
        "outputId": "00e03d64-1ef8-43bd-ebf9-3f0212dee6b9"
      },
      "source": [
        "# 22-2\n",
        "def e():\n",
        "    v = 5\n",
        "    print(v)   \n",
        "v= 1\n",
        "e()"
      ],
      "execution_count": 132,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "5\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "VOa2yupxy4Mk",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 34
        },
        "outputId": "3d9b91dc-463d-4bd1-b965-47e0a244ea56"
      },
      "source": [
        "# 22-3\n",
        "def f():\n",
        "    print(v)\n",
        "v= 1\n",
        "f()"
      ],
      "execution_count": 133,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "1\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "jUgiIdWXy4Oz",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 34
        },
        "outputId": "d48f6455-1115-4226-9b6f-a80888cdf474"
      },
      "source": [
        "# 22-4\n",
        "def g():\n",
        "    print(v+x)  \n",
        "v= 1\n",
        "x= 2\n",
        "g()"
      ],
      "execution_count": 134,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "3\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "igRVPn52y4RS",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 313
        },
        "outputId": "d5158b93-229f-4a3e-ed9e-c3141ec00097"
      },
      "source": [
        "# 22-5\n",
        "def h():\n",
        "    v += 5   \n",
        "v= 1\n",
        "h()"
      ],
      "execution_count": 135,
      "outputs": [
        {
          "output_type": "error",
          "ename": "UnboundLocalError",
          "evalue": "ignored",
          "traceback": [
            "\u001b[0;31m---------------------------------------------------------------------------\u001b[0m",
            "\u001b[0;31mUnboundLocalError\u001b[0m                         Traceback (most recent call last)",
            "\u001b[0;32m<ipython-input-135-e50d46b2f724>\u001b[0m in \u001b[0;36m<module>\u001b[0;34m()\u001b[0m\n\u001b[1;32m      2\u001b[0m     \u001b[0mv\u001b[0m \u001b[0;34m+=\u001b[0m \u001b[0;36m5\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m      3\u001b[0m \u001b[0mv\u001b[0m\u001b[0;34m=\u001b[0m \u001b[0;36m1\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0;32m----> 4\u001b[0;31m \u001b[0mh\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0m",
            "\u001b[0;32m<ipython-input-135-e50d46b2f724>\u001b[0m in \u001b[0;36mh\u001b[0;34m()\u001b[0m\n\u001b[1;32m      1\u001b[0m \u001b[0;32mdef\u001b[0m \u001b[0mh\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m:\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0;32m----> 2\u001b[0;31m     \u001b[0mv\u001b[0m \u001b[0;34m+=\u001b[0m \u001b[0;36m5\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0m\u001b[1;32m      3\u001b[0m \u001b[0mv\u001b[0m\u001b[0;34m=\u001b[0m \u001b[0;36m1\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m      4\u001b[0m \u001b[0mh\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n",
            "\u001b[0;31mUnboundLocalError\u001b[0m: local variable 'v' referenced before assignment"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "4MFQSsbpy4To",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 52
        },
        "outputId": "e843f0c2-0a18-4aa7-879a-2401f45599c0"
      },
      "source": [
        "# 22-6\n",
        "def odd_or_even(num):\n",
        "    num = num%2\n",
        "    if num == 1:\n",
        "        return \"odd\"\n",
        "    else:\n",
        "        return \"even\"\n",
        "num = 4 \n",
        "print(odd_or_even(num))   \n",
        "odd_or_even(5)"
      ],
      "execution_count": 136,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "even\n"
          ],
          "name": "stdout"
        },
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "'odd'"
            ]
          },
          "metadata": {
            "tags": []
          },
          "execution_count": 136
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "rPOLmlkPy4V2",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 260
        },
        "outputId": "828e189f-5338-46ab-faae-be425ef503c1"
      },
      "source": [
        "# 22-7\n",
        "def sing():\n",
        "    def stop(line):\n",
        "        print(\"STOP\", line)\n",
        "    stop(\"it's hammer time\")\n",
        "    stop(\"in the name of love\")\n",
        "    stop(\"hey, what’s that sound\")\n",
        "sing()\n",
        "stop()"
      ],
      "execution_count": 137,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "STOP it's hammer time\n",
            "STOP in the name of love\n",
            "STOP hey, what’s that sound\n"
          ],
          "name": "stdout"
        },
        {
          "output_type": "error",
          "ename": "NameError",
          "evalue": "ignored",
          "traceback": [
            "\u001b[0;31m---------------------------------------------------------------------------\u001b[0m",
            "\u001b[0;31mNameError\u001b[0m                                 Traceback (most recent call last)",
            "\u001b[0;32m<ipython-input-137-c843682fb486>\u001b[0m in \u001b[0;36m<module>\u001b[0;34m()\u001b[0m\n\u001b[1;32m      6\u001b[0m     \u001b[0mstop\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;34m\"hey, what’s that sound\"\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m      7\u001b[0m \u001b[0msing\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0;32m----> 8\u001b[0;31m \u001b[0mstop\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0m",
            "\u001b[0;31mNameError\u001b[0m: name 'stop' is not defined"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "J8zsfHM8y4YX",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 123
        },
        "outputId": "c2f66c2b-d287-443c-e97c-d282bd23e257"
      },
      "source": [
        "# 22-8\n",
        "def sandwich(kind_of_sandwich):\n",
        "    print(\"--------\")\n",
        "    print(kind_of_sandwich())\n",
        "    print(\"--------\")\n",
        "def blt():\n",
        "    my_blt = \" bacon\\n lettuce\\n tomato\"\n",
        "    return my_blt\n",
        "def breakfast():\n",
        "    my_ec = \" eggegg\\n cheese\"\n",
        "    return my_ec\n",
        "print(sandwich(blt))"
      ],
      "execution_count": 138,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "--------\n",
            " bacon\n",
            " lettuce\n",
            " tomato\n",
            "--------\n",
            "None\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "6SV_qCNZzHBy",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 105
        },
        "outputId": "fca9b029-92fd-462a-dda6-d83830189232"
      },
      "source": [
        "# 22-9\n",
        "def grumpy():\n",
        "    print(\"I am a grumpy cat:\")\n",
        "    def no_n_times(n): \n",
        "        print(\"No\", n, \"times...\")\n",
        "        def no_m_more_times(m): \n",
        "            print(\"...and no\", m, \"more times\")\n",
        "            for i in range(n+m):\n",
        "                print(\"no\")\n",
        "        return no_m_more_times\n",
        "    return no_n_times\n",
        "grumpy()(1)(1)"
      ],
      "execution_count": 144,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "I am a grumpy cat:\n",
            "No 1 times...\n",
            "...and no 1 more times\n",
            "no\n",
            "no\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "wGOJGl0pzHEJ",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 70
        },
        "outputId": "fcd74cb2-bb43-46ae-85aa-fb6f69761202"
      },
      "source": [
        "# 23-1\n",
        "word = \"bird\\n\"\n",
        "print(word) \n",
        "word = word.replace(\"\\n\", \"\") \n",
        "print(word)"
      ],
      "execution_count": 140,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "bird\n",
            "\n",
            "bird\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "FTAcNoM5zHLI",
        "colab_type": "code",
        "colab": {}
      },
      "source": [
        "# 23-2\n",
        "def read_file(file):\n",
        "    \"\"\"\n",
        "    file, a file object\n",
        "    Starting from the first line, it reads every\n",
        "    2 lines and stores them in a tuple.\n",
        "    Starting from the second line, it reads every\n",
        "    2 lines and stores them in a tuple.\n",
        "    Returns a tuple of the two tuples.\n",
        "    \"\"\"\n",
        "    first_every_2 =()\n",
        "    second_every_2 =()\n",
        "    line_count = 1   \n",
        "    for line in file:   \n",
        "        stripped_line = line.replace(\"\\n\",\"\")\n",
        "        if line_count%2 == 1:   \n",
        "            first_every_2 +=(stripped_line,)\n",
        "        elif line_count%2 == 0:   \n",
        "            second_every_2 +=(stripped_line,)\n",
        "        line_count += 1 \n",
        "    return(first_every_2, second_every_2) "
      ],
      "execution_count": 0,
      "outputs": []
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "B9zxNwBbzHIp",
        "colab_type": "code",
        "colab": {}
      },
      "source": [
        "# 23-3\n",
        "def sanitize(some_tuple):\n",
        "    \"\"\"\n",
        "    phones, a tuple of strings\n",
        "    Removes all spaces, dashes, and open/closed parentheses\n",
        "    in each string\n",
        "    Returns a tuple with cleaned up string elements\n",
        "    \"\"\"\n",
        "    clean_string =() \n",
        "    for st in some_tuple:\n",
        "        st = st.replace(\" \", \"\")\n",
        "        st = st.replace(\"-\", \"\")\n",
        "        st = st.replace(\"(\", \"\")\n",
        "        st = st.replace(\")\", \"\")\n",
        "        clean_string +=(st, ) \n",
        "    return clean_string"
      ],
      "execution_count": 0,
      "outputs": []
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "OHrClNkozHNV",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 242
        },
        "outputId": "0be457a5-30cf-47a9-88ce-01829d94f00b"
      },
      "source": [
        "# 23-4\n",
        "friends_file = open('friends.txt') \n",
        "(names, phones)= read_file(friends_file)\n",
        "print(names)   \n",
        "print(phones)\n",
        "clean_phones = sanitize(phones)\n",
        "print(clean_phones) \n",
        "friends_file.close()"
      ],
      "execution_count": 147,
      "outputs": [
        {
          "output_type": "error",
          "ename": "FileNotFoundError",
          "evalue": "ignored",
          "traceback": [
            "\u001b[0;31m---------------------------------------------------------------------------\u001b[0m",
            "\u001b[0;31mFileNotFoundError\u001b[0m                         Traceback (most recent call last)",
            "\u001b[0;32m<ipython-input-147-b5df2baa957c>\u001b[0m in \u001b[0;36m<module>\u001b[0;34m()\u001b[0m\n\u001b[0;32m----> 1\u001b[0;31m \u001b[0mfriends_file\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0mopen\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;34m'friends.txt'\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0m\u001b[1;32m      2\u001b[0m \u001b[0;34m(\u001b[0m\u001b[0mnames\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0mphones\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m=\u001b[0m \u001b[0mread_file\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0mfriends_file\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m      3\u001b[0m \u001b[0mprint\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0mnames\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m      4\u001b[0m \u001b[0mprint\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0mphones\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m      5\u001b[0m \u001b[0mclean_phones\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0msanitize\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0mphones\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n",
            "\u001b[0;31mFileNotFoundError\u001b[0m: [Errno 2] No such file or directory: 'friends.txt'"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "upegEA43zHRL",
        "colab_type": "code",
        "colab": {}
      },
      "source": [
        "# 23-5\n",
        "def get_unique_area_codes():\n",
        "    \"\"\"\n",
        "    Returns a tuple of all unique area codes in phones\n",
        "    \"\"\"\n",
        "    area_codes =()\n",
        "    for ph in phones: \n",
        "        if ph[0:3] not in area_codes:  \n",
        "            area_codes +=(ph[0:3], )   \n",
        "    return area_codes"
      ],
      "execution_count": 0,
      "outputs": []
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "9qxvyh5uzHTX",
        "colab_type": "code",
        "colab": {}
      },
      "source": [
        "# 23-6\n",
        "def get_states(some_areacodes):\n",
        "    \"\"\"\n",
        "    some_areacodes, a tuple of area codes\n",
        "    Returns a tuple of the states associated with those area\n",
        "codes\n",
        "    \"\"\"\n",
        "    states =()\n",
        "    for ac in some_areacodes:\n",
        "        if ac not in all_areacodes: states +=(\"BAD AREACODE\", )\n",
        "        else:\n",
        "            index = all_areacodes.index(ac)\n",
        "            states +=(all_places[index], )\n",
        "    return states"
      ],
      "execution_count": 0,
      "outputs": []
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "CmYtfj7pzHPZ",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 242
        },
        "outputId": "12581120-02eb-4824-86b8-51e602133d12"
      },
      "source": [
        "# 23-7\n",
        "def analyze_friends(names, phones, all_areacodes, all_places):\n",
        "    \"\"\"\n",
        "    names, a tuple of friend names\n",
        "    phones, a tuple of phone numbers without special symbols\n",
        "    all_areacodes, a tuple of strings for the area codes\n",
        "    all_places, a tuple of strings for the US states\n",
        "    Prints out how many friends you have and every unique\n",
        "    state that is represented by their phone numbers.\n",
        "    \"\"\"\n",
        "def get_unique_area_codes():\n",
        "    \"\"\"\n",
        "    Returns a tuple of all unique area codes in phones\n",
        "    \"\"\"\n",
        "    area_codes =()\n",
        "    for ph in phones:\n",
        "        if ph[0:3] not in area_codes: area_codes +=(ph[0:3], )\n",
        "    return area_codes\n",
        "\n",
        "def get_states(some_areacodes):\n",
        "    \"\"\"\n",
        "    some_area_codes, a tuple of area codes\n",
        "    Returns a tuple of the states associated with those\n",
        "    area codes\n",
        "    \"\"\"\n",
        "    states =()\n",
        "    for ac in some_areacodes:\n",
        "        if ac not in all_areacodes:\n",
        "            states +=(\"BAD AREACODE\", )\n",
        "    else:\n",
        "        index = all_areacodes.index(ac)\n",
        "        states +=(all_places[index], )\n",
        "    return states\n",
        "num_friends = len(names)\n",
        "unique_area_codes = get_unique_area_codes()\n",
        "unique_states = get_states(unique_area_codes)\n",
        "print(\"You have\", num_friends, \"friends!\")\n",
        "print(\"They live in\", unique_states)"
      ],
      "execution_count": 151,
      "outputs": [
        {
          "output_type": "error",
          "ename": "NameError",
          "evalue": "ignored",
          "traceback": [
            "\u001b[0;31m---------------------------------------------------------------------------\u001b[0m",
            "\u001b[0;31mNameError\u001b[0m                                 Traceback (most recent call last)",
            "\u001b[0;32m<ipython-input-151-5e8ed6111f16>\u001b[0m in \u001b[0;36m<module>\u001b[0;34m()\u001b[0m\n\u001b[1;32m     31\u001b[0m         \u001b[0mstates\u001b[0m \u001b[0;34m+=\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0mall_places\u001b[0m\u001b[0;34m[\u001b[0m\u001b[0mindex\u001b[0m\u001b[0;34m]\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m     32\u001b[0m     \u001b[0;32mreturn\u001b[0m \u001b[0mstates\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0;32m---> 33\u001b[0;31m \u001b[0mnum_friends\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0mlen\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0mnames\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0m\u001b[1;32m     34\u001b[0m \u001b[0munique_area_codes\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0mget_unique_area_codes\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m     35\u001b[0m \u001b[0munique_states\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0mget_states\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0munique_area_codes\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n",
            "\u001b[0;31mNameError\u001b[0m: name 'names' is not defined"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "FUbYXs3IzHGq",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 242
        },
        "outputId": "53c9f243-4f72-430b-d5a3-7fffe9b76a7e"
      },
      "source": [
        "# 23-8\n",
        "friends_file = open('friends.txt')\n",
        "(names, phones)= read_file(friends_file)\n",
        "areacodes_file = open('map_areacodes_states.txt')\n",
        "(areacodes, states)= read_file(areacodes_file)\n",
        "clean_phones = sanitize(phones)\n",
        "analyze_friends(names, clean_phones, areacodes, states)\n",
        "friends_file.close()\n",
        "areacodes_file.close()"
      ],
      "execution_count": 152,
      "outputs": [
        {
          "output_type": "error",
          "ename": "FileNotFoundError",
          "evalue": "ignored",
          "traceback": [
            "\u001b[0;31m---------------------------------------------------------------------------\u001b[0m",
            "\u001b[0;31mFileNotFoundError\u001b[0m                         Traceback (most recent call last)",
            "\u001b[0;32m<ipython-input-152-4cc05e445772>\u001b[0m in \u001b[0;36m<module>\u001b[0;34m()\u001b[0m\n\u001b[0;32m----> 1\u001b[0;31m \u001b[0mfriends_file\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0mopen\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;34m'friends.txt'\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0m\u001b[1;32m      2\u001b[0m \u001b[0;34m(\u001b[0m\u001b[0mnames\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0mphones\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m=\u001b[0m \u001b[0mread_file\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0mfriends_file\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m      3\u001b[0m \u001b[0mareacodes_file\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0mopen\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;34m'map_areacodes_states.txt'\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m      4\u001b[0m \u001b[0;34m(\u001b[0m\u001b[0mareacodes\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0mstates\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m=\u001b[0m \u001b[0mread_file\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0mareacodes_file\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m      5\u001b[0m \u001b[0mclean_phones\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0msanitize\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0mphones\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n",
            "\u001b[0;31mFileNotFoundError\u001b[0m: [Errno 2] No such file or directory: 'friends.txt'"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "tksu8Mf7ze6-",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 105
        },
        "outputId": "b1ce08a5-dcf2-4c16-f931-6fbe8a45ba8d"
      },
      "source": [
        "# 25-1\n",
        "years = [1984, 1986, 1988, 1988]\n",
        "print(len(years))\n",
        "print(years.count(1988))\n",
        "print(years.count(2017))\n",
        "print(years.index(1986))\n",
        "print(years.index(1988))"
      ],
      "execution_count": 153,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "4\n",
            "2\n",
            "0\n",
            "1\n",
            "2\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "o1tHaJA2ze_3",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 70
        },
        "outputId": "2a9f912f-0e85-49fe-8c24-8876bf139a70"
      },
      "source": [
        "# 25-2\n",
        "first3letters = []\n",
        "first3letters.append(\"a\")\n",
        "first3letters.append(\"c\")\n",
        "first3letters.insert(1, \"b\")\n",
        "print(first3letters)\n",
        "last3letters = [\"x\", \"y\", \"z\"]\n",
        "first3letters.extend(last3letters)\n",
        "print(first3letters)\n",
        "last3letters.extend(first3letters)\n",
        "print(last3letters)"
      ],
      "execution_count": 154,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "['a', 'b', 'c']\n",
            "['a', 'b', 'c', 'x', 'y', 'z']\n",
            "['x', 'y', 'z', 'a', 'b', 'c', 'x', 'y', 'z']\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "k1fHzJFwzfEW",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 87
        },
        "outputId": "b1840505-073d-4b23-b72c-18bf40e36e36"
      },
      "source": [
        "# 25-3\n",
        "polite = [\"please\", \"and\", \"thank\", \"you\"]   \n",
        "print(polite.pop())\n",
        "print(polite)\n",
        "print(polite.pop(1)) \n",
        "print(polite)"
      ],
      "execution_count": 155,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "you\n",
            "['please', 'and', 'thank']\n",
            "and\n",
            "['please', 'thank']\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "OufqORlgzfJS",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 70
        },
        "outputId": "b98e471f-6d84-438e-e0dd-a6fb5ad10c88"
      },
      "source": [
        "# 25-4\n",
        "colors = [\"red\", \"blue\", \"yellow\"]\n",
        "colors[0] = \"orange\"\n",
        "print(colors)\n",
        "colors[1] = \"green\"\n",
        "print(colors)\n",
        "colors[2] = \"purple\"\n",
        "print(colors)"
      ],
      "execution_count": 156,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "['orange', 'blue', 'yellow']\n",
            "['orange', 'green', 'yellow']\n",
            "['orange', 'green', 'purple']\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "crGUWpRIzfMW",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 70
        },
        "outputId": "6faf5749-06dc-4a96-cc35-7ac77b317643"
      },
      "source": [
        "# 26-1\n",
        "heights = [1.4, 1.3, 1.5, 2, 1.4, 1.5, 1]\n",
        "\n",
        "heights.reverse()  \n",
        "print(heights)\n",
        "\n",
        "heights.sort()  \n",
        "print(heights)\n",
        "\n",
        "heights.reverse()\n",
        "print(heights)"
      ],
      "execution_count": 157,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "[1, 1.5, 1.4, 2, 1.5, 1.3, 1.4]\n",
            "[1, 1.3, 1.4, 1.4, 1.5, 1.5, 2]\n",
            "[2, 1.5, 1.5, 1.4, 1.4, 1.3, 1]\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "vyCxLy-kzfO7",
        "colab_type": "code",
        "colab": {}
      },
      "source": [
        "# 26-2\n",
        "L = [[], [], []]\n",
        "L[0] = [1, 2, 3]\n",
        "L[1].append('t')\n",
        "L[1].append('o')\n",
        "L[1][0] = 'd'"
      ],
      "execution_count": 0,
      "outputs": []
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "LsJZEzV-zfRi",
        "colab_type": "code",
        "colab": {}
      },
      "source": [
        "# 26-3\n",
        "x = 'x' \n",
        "o = 'o'\n",
        "e = '_'\n",
        "board = [[x, e, o], [e, x, o], [x, e, e]]"
      ],
      "execution_count": 0,
      "outputs": []
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "rPchLfQwzfHU",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 34
        },
        "outputId": "ab2d46f5-9f74-4781-90db-bdc5ca9014f4"
      },
      "source": [
        "# 26-4\n",
        "stack = []\n",
        "cook = ['b', 'b', 'b']\n",
        "stack.extend(cook)\n",
        "stack.pop()\n",
        "stack.pop()\n",
        "cook = ['c', 'c']\n",
        "stack.extend(cook)\n",
        "stack.pop()\n",
        "cook = ['b', 'b']\n",
        "stack.extend(cook)\n",
        "stack.pop()\n",
        "stack.pop()\n",
        "stack.pop()"
      ],
      "execution_count": 160,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "'c'"
            ]
          },
          "metadata": {
            "tags": []
          },
          "execution_count": 160
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "6Jp7zLrAzfCS",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 34
        },
        "outputId": "ae3ac67b-7586-4e1e-c636-bc21ac1367b4"
      },
      "source": [
        "# 26-5\n",
        "line = []\n",
        "line.append('Ana')\n",
        "line.append('Bob')\n",
        "line.pop(0)\n",
        "line.append('Claire')\n",
        "line.append('Dave')\n",
        "line.pop(0)\n",
        "line.pop(0)\n",
        "line.pop(0)"
      ],
      "execution_count": 161,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "'Dave'"
            ]
          },
          "metadata": {
            "tags": []
          },
          "execution_count": 161
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "rdiEdQAOze95",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 70
        },
        "outputId": "7138bc8d-0327-4d82-d6bc-90f33d0acce4"
      },
      "source": [
        "# 27-1\n",
        "legs = {} \n",
        "legs[\"human\"] = 2\n",
        "legs[\"cat\"] = 4\n",
        "legs[\"snake\"] = 0\n",
        "print(len(legs))\n",
        "legs[\"cat\"] = 3\n",
        "print(len(legs))\n",
        "print(legs)"
      ],
      "execution_count": 162,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "3\n",
            "3\n",
            "{'human': 2, 'cat': 3, 'snake': 0}\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "B414n_8Nzsbu",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 34
        },
        "outputId": "32e16acf-1951-4fd0-8d66-3a94c4a3d195"
      },
      "source": [
        "# 27-2\n",
        "household = {\"person\":4, \"cat\":2, \"dog\":1, \"fish\":2}\n",
        "removed = household.pop(\"fish\")\n",
        "print(removed)"
      ],
      "execution_count": 163,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "2\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "Bo0gC2rtzseJ",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 176
        },
        "outputId": "9eb42de4-3048-4d90-b188-4a4d4ab311b0"
      },
      "source": [
        "# 27-3\n",
        "grades = {}\n",
        "grades[\"Chris\"] = [100, 70]\n",
        "grades[\"Angela\"] = [90, 100]\n",
        "grades[\"Bruce\"] = [80, 40]\n",
        "grades[\"Stacey\"] = [70, 70]\n",
        "for student in grades.keys():\n",
        "    print(student)\n",
        "for quizzes in grades.values():\n",
        "    print(sum(quizzes)/2)\n",
        "for student in grades.keys():\n",
        "    scores = grades[student]\n",
        "    grades[student].append(sum(scores)/2)\n",
        "print(grades)"
      ],
      "execution_count": 164,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "Chris\n",
            "Angela\n",
            "Bruce\n",
            "Stacey\n",
            "85.0\n",
            "95.0\n",
            "60.0\n",
            "70.0\n",
            "{'Chris': [100, 70, 85.0], 'Angela': [90, 100, 95.0], 'Bruce': [80, 40, 60.0], 'Stacey': [70, 70, 70.0]}\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "ugu2BZEXzsiY",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 34
        },
        "outputId": "96700c10-861a-41f7-9015-c331b6db34d5"
      },
      "source": [
        "# 27-4\n",
        "lyrics = \"Happy birthday to you Happy birthday to you \" +\\\n",
        "         \"Happy birthday dear Happy birthday to you\"\n",
        "counts = {}\n",
        "words = lyrics.split(\" \")\n",
        "for w in words:\n",
        "    w = w.lower()\n",
        "    if w not in counts:\n",
        "        counts[w] = 1\n",
        "    else:\n",
        "        counts[w] += 1\n",
        "print(counts) "
      ],
      "execution_count": 165,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "{'happy': 4, 'birthday': 4, 'to': 3, 'you': 3, 'dear': 1}\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "bKFuj1Tozsm0",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 70
        },
        "outputId": "9ef83e66-77cc-47d3-9519-42ad96f949ac"
      },
      "source": [
        "# 27-5\n",
        "def square(x):\n",
        "    return x*x\n",
        "\n",
        "def circle(r):\n",
        "    return 3.14*r*r\n",
        "\n",
        "def equilateraltriangle(s):\n",
        "    return(s*s)*(3**0.5)/4\n",
        "\n",
        "areas = {\"sq\": square, \"ci\": circle, \"eqtri\":\n",
        "         equilateraltriangle}\n",
        "n= 2\n",
        "print(areas[\"sq\"](n))\n",
        "print(areas[\"ci\"](n))\n",
        "print(areas[\"eqtri\"](n))"
      ],
      "execution_count": 166,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "4\n",
            "12.56\n",
            "1.7320508075688772\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "YFp90DJNzste",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 70
        },
        "outputId": "86e57ff4-355a-4c1b-b02e-ebeaab630316"
      },
      "source": [
        "# 28-1\n",
        "def add_word(d, word, definition):\n",
        "    \"\"\" d, dict that maps strings to lists of strings\n",
        "        word, a string\n",
        "        definition, a string\n",
        "        Mutates d by adding the entry word:definition\n",
        "        If word is already in d, append definition to word’s value list\n",
        "        Does not return anything\n",
        "     \"\"\"\n",
        "    if word in d:\n",
        "        d[word].append(definition)\n",
        "    else:\n",
        "        d[word] = [definition]\n",
        "\n",
        "words = {}\n",
        "add_word(words, 'box', 'fight') \n",
        "print(words)\n",
        "add_word(words, 'box', 'container')\n",
        "print(words)\n",
        "add_word(words, 'ox', 'animal') \n",
        "print(words)"
      ],
      "execution_count": 167,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "{'box': ['fight']}\n",
            "{'box': ['fight', 'container']}\n",
            "{'box': ['fight', 'container'], 'ox': ['animal']}\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "7u7CVSANzs0G",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 224
        },
        "outputId": "87ec1975-63ef-4af9-9c28-29a9b3b27c95"
      },
      "source": [
        "# 28-2\n",
        "songs = {\"Wannabe\": 1, \"Roar\": 1, \"Let It Be\": 5, \"Red Corvette\": 4}   \n",
        "for s in songs.keys():\n",
        "    if songs[s] == 1:\n",
        "        songs.pop(s)"
      ],
      "execution_count": 169,
      "outputs": [
        {
          "output_type": "error",
          "ename": "RuntimeError",
          "evalue": "ignored",
          "traceback": [
            "\u001b[0;31m---------------------------------------------------------------------------\u001b[0m",
            "\u001b[0;31mRuntimeError\u001b[0m                              Traceback (most recent call last)",
            "\u001b[0;32m<ipython-input-169-3089b7ba46f5>\u001b[0m in \u001b[0;36m<module>\u001b[0;34m()\u001b[0m\n\u001b[1;32m      1\u001b[0m \u001b[0msongs\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0;34m{\u001b[0m\u001b[0;34m\"Wannabe\"\u001b[0m\u001b[0;34m:\u001b[0m \u001b[0;36m1\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0;34m\"Roar\"\u001b[0m\u001b[0;34m:\u001b[0m \u001b[0;36m1\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0;34m\"Let It Be\"\u001b[0m\u001b[0;34m:\u001b[0m \u001b[0;36m5\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0;34m\"Red Corvette\"\u001b[0m\u001b[0;34m:\u001b[0m \u001b[0;36m4\u001b[0m\u001b[0;34m}\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0;32m----> 2\u001b[0;31m \u001b[0;32mfor\u001b[0m \u001b[0ms\u001b[0m \u001b[0;32min\u001b[0m \u001b[0msongs\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mkeys\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m:\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0m\u001b[1;32m      3\u001b[0m     \u001b[0;32mif\u001b[0m \u001b[0msongs\u001b[0m\u001b[0;34m[\u001b[0m\u001b[0ms\u001b[0m\u001b[0;34m]\u001b[0m \u001b[0;34m==\u001b[0m \u001b[0;36m1\u001b[0m\u001b[0;34m:\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m      4\u001b[0m         \u001b[0msongs\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mpop\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0ms\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n",
            "\u001b[0;31mRuntimeError\u001b[0m: dictionary changed size during iteration"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "XdvURpdFzsyW",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 34
        },
        "outputId": "d7641e63-e606-46da-a808-cbf9df3c7bfa"
      },
      "source": [
        "# 28-3\n",
        "songs = [1, 1, 8, 4]\n",
        "for s in songs:\n",
        "    if s == 1: songs.pop(s)\n",
        "print(songs)"
      ],
      "execution_count": 170,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "[1, 8, 4]\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "XEDfmBfqzswJ",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 34
        },
        "outputId": "db85485d-168d-424a-8231-3c2b9c1b225d"
      },
      "source": [
        "# 28-4\n",
        "songs = [1, 1, 5, 4]\n",
        "songs_copy = songs.copy() \n",
        "songs = []\n",
        "for s in songs_copy:     \n",
        "    if s != 1:\n",
        "        songs.append(s) \n",
        "print(songs)"
      ],
      "execution_count": 171,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "[5, 4]\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "00GQKleMzsrD",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 348
        },
        "outputId": "35272a8a-ac08-45a3-e71f-39cbcf67c178"
      },
      "source": [
        "# 29-1\n",
        "def read_text(filename):\n",
        "    \"\"\"\n",
        "    filename: string, name of file to read\n",
        "    returns: string, contains all file contents\n",
        "    \"\"\"\n",
        "    inFile = open(filename)\n",
        "    line = inFile.read()\n",
        "    inFile.close()\n",
        "    return line\n",
        "text = read_text(\"sonnet18.txt\")\n",
        "print(text)"
      ],
      "execution_count": 172,
      "outputs": [
        {
          "output_type": "error",
          "ename": "FileNotFoundError",
          "evalue": "ignored",
          "traceback": [
            "\u001b[0;31m---------------------------------------------------------------------------\u001b[0m",
            "\u001b[0;31mFileNotFoundError\u001b[0m                         Traceback (most recent call last)",
            "\u001b[0;32m<ipython-input-172-b66fa314e033>\u001b[0m in \u001b[0;36m<module>\u001b[0;34m()\u001b[0m\n\u001b[1;32m      8\u001b[0m     \u001b[0minFile\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mclose\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m      9\u001b[0m     \u001b[0;32mreturn\u001b[0m \u001b[0mline\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0;32m---> 10\u001b[0;31m \u001b[0mtext\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0mread_text\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;34m\"sonnet18.txt\"\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0m\u001b[1;32m     11\u001b[0m \u001b[0mprint\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0mtext\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n",
            "\u001b[0;32m<ipython-input-172-b66fa314e033>\u001b[0m in \u001b[0;36mread_text\u001b[0;34m(filename)\u001b[0m\n\u001b[1;32m      4\u001b[0m     \u001b[0mreturns\u001b[0m\u001b[0;34m:\u001b[0m \u001b[0mstring\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0mcontains\u001b[0m \u001b[0mall\u001b[0m \u001b[0mfile\u001b[0m \u001b[0mcontents\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m      5\u001b[0m     \"\"\"\n\u001b[0;32m----> 6\u001b[0;31m     \u001b[0minFile\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0mopen\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0mfilename\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0m\u001b[1;32m      7\u001b[0m     \u001b[0mline\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0minFile\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mread\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m      8\u001b[0m     \u001b[0minFile\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mclose\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n",
            "\u001b[0;31mFileNotFoundError\u001b[0m: [Errno 2] No such file or directory: 'sonnet18.txt'"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "j86l_rH6zspc",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 135
        },
        "outputId": "3de6815f-a8d7-47d3-d6a7-bdefbbbde227"
      },
      "source": [
        "# 29-2\n",
        "import string\n",
        "def find_words(text):\n",
        "    \"\"\"\n",
        "    text: string\n",
        "    returns: list of words from input text\n",
        "    \"\"\"\n",
        "    text = text.replace(\"\\n\", \" \")\n",
        "    for char in string.punctuation:   \n",
        "        text = text.replace(char, \"\")   \n",
        "     words = text.split(\" \")\n",
        "     return words \n",
        "words = find_words(text)"
      ],
      "execution_count": 173,
      "outputs": [
        {
          "output_type": "error",
          "ename": "IndentationError",
          "evalue": "ignored",
          "traceback": [
            "\u001b[0;36m  File \u001b[0;32m\"<ipython-input-173-2bfb5c7e8cff>\"\u001b[0;36m, line \u001b[0;32m10\u001b[0m\n\u001b[0;31m    words = text.split(\" \")\u001b[0m\n\u001b[0m                           ^\u001b[0m\n\u001b[0;31mIndentationError\u001b[0m\u001b[0;31m:\u001b[0m unindent does not match any outer indentation level\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "r8EOeYTtzslB",
        "colab_type": "code",
        "colab": {}
      },
      "source": [
        "# 29-3\n",
        "def frequencies(words):\n",
        "    \"\"\"\n",
        "    words: list of words\n",
        "    returns: frequency dictionary for input words\n",
        "    \"\"\"\n",
        "    freq_dict = {}\n",
        "    for word in words:\n",
        "        if word in freq_dict:   \n",
        "            freq_dict[word] += 1  \n",
        "        else:\n",
        "            freq_dict[word] = 1\n",
        "    return freq_dict\n",
        "freq_dict = frequencies(words)"
      ],
      "execution_count": 0,
      "outputs": []
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "I7AAZArDzsgx",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 135
        },
        "outputId": "060aa251-55a5-44b9-cee8-5c1071249938"
      },
      "source": [
        "# 29-4\n",
        "def calculate_similarity(dict1, dict2):\n",
        "    \"\"\"\n",
        "    dict1: frequency dictionary for one text\n",
        "    dict2: frequency dictionary for another text\n",
        "    returns: float, representing how similar both texts are to\n",
        "each other\n",
        "    \"\"\"\n",
        "    diff = 0\n",
        "    total = 0\n",
        "    for word in dict1.keys():\n",
        "        if word in dict2.keys():\n",
        "            diff += abs(dict1[word] - dict2[word])\n",
        "        else:\n",
        "            diff += dict1[word]\n",
        "\n",
        "    for word in dict2.keys():\n",
        "        if word not in dict1.keys():   \n",
        "            diff += dict2[word]\n",
        "    total = sum(dict1.values()) + sum(dict2.values())\n",
        "    difference = diff / total\n",
        "    similar = 1.0– difference\n",
        "    return round(similar, 2)"
      ],
      "execution_count": 175,
      "outputs": [
        {
          "output_type": "error",
          "ename": "SyntaxError",
          "evalue": "ignored",
          "traceback": [
            "\u001b[0;36m  File \u001b[0;32m\"<ipython-input-175-35af08705d9e>\"\u001b[0;36m, line \u001b[0;32m21\u001b[0m\n\u001b[0;31m    similar = 1.0– difference\u001b[0m\n\u001b[0m                 ^\u001b[0m\n\u001b[0;31mSyntaxError\u001b[0m\u001b[0;31m:\u001b[0m invalid character in identifier\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "VNBKD9TF0Ak0",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 366
        },
        "outputId": "76356b44-d91a-428a-bcf4-b39c81bff8db"
      },
      "source": [
        "# 29-5\n",
        "text_1 = read_text(\"sonnet18.txt\")\n",
        "text_2 = read_text(\"sonnet19.txt\")\n",
        "words_1 = find_words(text_1)\n",
        "words_2 = find_words(text_2)\n",
        "freq_dict_1 = frequencies(words_1)\n",
        "freq_dict_2 = frequencies(words_2)\n",
        "print(calculate_similarity(freq_dict_1, freq_dict_2))"
      ],
      "execution_count": 176,
      "outputs": [
        {
          "output_type": "error",
          "ename": "FileNotFoundError",
          "evalue": "ignored",
          "traceback": [
            "\u001b[0;31m---------------------------------------------------------------------------\u001b[0m",
            "\u001b[0;31mFileNotFoundError\u001b[0m                         Traceback (most recent call last)",
            "\u001b[0;32m<ipython-input-176-03459644a893>\u001b[0m in \u001b[0;36m<module>\u001b[0;34m()\u001b[0m\n\u001b[0;32m----> 1\u001b[0;31m \u001b[0mtext_1\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0mread_text\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;34m\"sonnet18.txt\"\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0m\u001b[1;32m      2\u001b[0m \u001b[0mtext_2\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0mread_text\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;34m\"sonnet19.txt\"\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m      3\u001b[0m \u001b[0mwords_1\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0mfind_words\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0mtext_1\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m      4\u001b[0m \u001b[0mwords_2\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0mfind_words\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0mtext_2\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m      5\u001b[0m \u001b[0mfreq_dict_1\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0mfrequencies\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0mwords_1\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n",
            "\u001b[0;32m<ipython-input-172-b66fa314e033>\u001b[0m in \u001b[0;36mread_text\u001b[0;34m(filename)\u001b[0m\n\u001b[1;32m      4\u001b[0m     \u001b[0mreturns\u001b[0m\u001b[0;34m:\u001b[0m \u001b[0mstring\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0mcontains\u001b[0m \u001b[0mall\u001b[0m \u001b[0mfile\u001b[0m \u001b[0mcontents\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m      5\u001b[0m     \"\"\"\n\u001b[0;32m----> 6\u001b[0;31m     \u001b[0minFile\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0mopen\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0mfilename\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0m\u001b[1;32m      7\u001b[0m     \u001b[0mline\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0minFile\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mread\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m      8\u001b[0m     \u001b[0minFile\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mclose\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n",
            "\u001b[0;31mFileNotFoundError\u001b[0m: [Errno 2] No such file or directory: 'sonnet18.txt'"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "I3adTA4c0C6s",
        "colab_type": "code",
        "colab": {}
      },
      "source": [
        "# 31-1\n",
        "class Rectangle:\n",
        "    \"\"\"\n",
        "    a rectangle object with a length and a width\n",
        "    \"\"\"\n",
        "    def __init__(self, length, width):\n",
        "        self.length = length\n",
        "        self.width = width\n",
        "    def set_length(self, length):\n",
        "        self.length = length\n",
        "    def set_width(self, width):\n",
        "        self.width = width"
      ],
      "execution_count": 0,
      "outputs": []
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "-d8DNJ7s0Apn",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 123
        },
        "outputId": "9dd14479-566b-417c-faf7-1ef4309c2ff8"
      },
      "source": [
        "# 32-2\n",
        "class Stack:\n",
        "    def __init__( self):\n",
        "        self.stack = []\n",
        "    def get_stack_elements(self):\n",
        "        return self.stack.copy()   \n",
        "    def add_one(self, item):\n",
        "        self.stack.append(item)\n",
        "    def add_many(self, item, n):\n",
        "        for i in range(n):\n",
        "            self.stack.append(item)\n",
        "    def remove_one(self):\n",
        "        self.stack.pop()\n",
        "    def remove_many(self , n):\n",
        "        for i in range(n):\n",
        "            self.stack.pop()\n",
        "    def size(self):\n",
        "        return len(self.stack)\n",
        "    def prettyprint(self):\n",
        "        for thing in self.stack[::-1]:\n",
        "            print('|_', thing, '_|')\n",
        "\n",
        "\n",
        "\n",
        "pancakes = Stack()\n",
        "pancakes.add_one(\"blueberry\")\n",
        "pancakes.add_many(\"chocolate\", 4)\n",
        "print(pancakes.size())\n",
        "pancakes.remove_one()\n",
        "print(pancakes.size())\n",
        "pancakes.prettyprint()"
      ],
      "execution_count": 178,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "5\n",
            "4\n",
            "|_ chocolate _|\n",
            "|_ chocolate _|\n",
            "|_ chocolate _|\n",
            "|_ blueberry _|\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "NjSuUN2y0A1J",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 242
        },
        "outputId": "763312d6-f668-4f1b-b456-d34e2f782e54"
      },
      "source": [
        "# 32-3\n",
        "class Stack:\n",
        "    def __init__( self):\n",
        "        self.stack = []\n",
        "    def get_stack_elements(self):\n",
        "        return self.stack.copy()   \n",
        "    def add_one(self, item):\n",
        "        self.stack.append(item)\n",
        "    def add_many(self, item, n):\n",
        "        for i in range(n):\n",
        "            self.stack.append(item)\n",
        "    def remove_one(self):\n",
        "        self.stack.pop()\n",
        "    def remove_many(self , n):\n",
        "        for i in range(n):\n",
        "            self.stack.pop()\n",
        "    def size(self):\n",
        "        return len(self.stack)\n",
        "    def prettyprint(self):\n",
        "        for thing in self.stack[::-1]:\n",
        "            print('|_', thing, '_|')\n",
        "            \n",
        "\n",
        "circles = Stack()\n",
        "one_circle = Circle()\n",
        "one_circle.change_radius(2)\n",
        "circles.add_one(one_circle)\n",
        "for i in range(5):\n",
        "    one_circle = Circle()\n",
        "    one_circle.change_radius(1)\n",
        "    circles.add_one(one_circle)\n",
        "print(circles.size())\n",
        "circles.prettyprint()"
      ],
      "execution_count": 179,
      "outputs": [
        {
          "output_type": "error",
          "ename": "NameError",
          "evalue": "ignored",
          "traceback": [
            "\u001b[0;31m---------------------------------------------------------------------------\u001b[0m",
            "\u001b[0;31mNameError\u001b[0m                                 Traceback (most recent call last)",
            "\u001b[0;32m<ipython-input-179-92bf1add750b>\u001b[0m in \u001b[0;36m<module>\u001b[0;34m()\u001b[0m\n\u001b[1;32m     22\u001b[0m \u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m     23\u001b[0m \u001b[0mcircles\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0mStack\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0;32m---> 24\u001b[0;31m \u001b[0mone_circle\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0mCircle\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0m\u001b[1;32m     25\u001b[0m \u001b[0mone_circle\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mchange_radius\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;36m2\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m     26\u001b[0m \u001b[0mcircles\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0madd_one\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0mone_circle\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n",
            "\u001b[0;31mNameError\u001b[0m: name 'Circle' is not defined"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "DSk3GUVI0A6J",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 242
        },
        "outputId": "4815da59-85c3-4d86-be19-8a0ff5adc0e3"
      },
      "source": [
        "# 32-4\n",
        "class Stack:\n",
        "    def __init__( self):\n",
        "        self.stack = []\n",
        "    def get_stack_elements(self):\n",
        "        return self.stack.copy()   \n",
        "    def add_one(self, item):\n",
        "        self.stack.append(item)\n",
        "    def add_many(self, item, n):\n",
        "        for i in range(n):\n",
        "            self.stack.append(item)\n",
        "    def remove_one(self):\n",
        "        self.stack.pop()\n",
        "    def remove_many(self , n):\n",
        "        for i in range(n):\n",
        "            self.stack.pop()\n",
        "    def size(self):\n",
        "        return len(self.stack)\n",
        "    def prettyprint(self):\n",
        "        for thing in self.stack[::-1]:\n",
        "            print('|_', thing, '_|')\n",
        "\n",
        "circles = Stack()\n",
        "one_circle = Circle()\n",
        "one_circle.change_radius(2)\n",
        "circles.add_one(one_circle)\n",
        "one_circle = Circle()\n",
        "one_circle.change_radius(1)\n",
        "circles.add_many(one_circle, 5)\n",
        "print(circles.size())\n",
        "circles.prettyprint()"
      ],
      "execution_count": 180,
      "outputs": [
        {
          "output_type": "error",
          "ename": "NameError",
          "evalue": "ignored",
          "traceback": [
            "\u001b[0;31m---------------------------------------------------------------------------\u001b[0m",
            "\u001b[0;31mNameError\u001b[0m                                 Traceback (most recent call last)",
            "\u001b[0;32m<ipython-input-180-8fce360a61c1>\u001b[0m in \u001b[0;36m<module>\u001b[0;34m()\u001b[0m\n\u001b[1;32m     21\u001b[0m \u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m     22\u001b[0m \u001b[0mcircles\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0mStack\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0;32m---> 23\u001b[0;31m \u001b[0mone_circle\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0mCircle\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0m\u001b[1;32m     24\u001b[0m \u001b[0mone_circle\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mchange_radius\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;36m2\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m     25\u001b[0m \u001b[0mcircles\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0madd_one\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0mone_circle\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n",
            "\u001b[0;31mNameError\u001b[0m: name 'Circle' is not defined"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "hdC1t6hR0A4Q",
        "colab_type": "code",
        "colab": {}
      },
      "source": [
        "# 33-1\n",
        "class Player:\n",
        "    \"\"\" 玩家 \"\"\"\n",
        "    def __init__(self, name):\n",
        "        \"\"\" 指定玩家姓名並生成空串列 \"\"\"\n",
        "        self.hand = []\n",
        "        self.name = name\n",
        "def get_name(self):\n",
        "    \"\"\" 回傳玩家姓名 \"\"\"\n",
        "    return self.name\n"
      ],
      "execution_count": 0,
      "outputs": []
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "EFc9d9tM0K2U",
        "colab_type": "code",
        "colab": {}
      },
      "source": [
        "# 33-2\n",
        "class Player:\n",
        "    \"\"\" 玩家 \"\"\"\n",
        "    def __init__(self, name):\n",
        "        \"\"\" 指定玩家姓名並生成空串列 \"\"\"\n",
        "        self.hand = []\n",
        "        self.name = name\n",
        "    def get_name(self):\n",
        "        \"\"\" 回傳玩家姓名 \"\"\"\n",
        "        return self.name\n",
        "\n",
        "    def add_card_to_hand(self, card):\n",
        "        if card != None:\n",
        "            self.hand.append(card)\n",
        "    def remove_card_from_hand(self, card):     \n",
        "        self.hand.remove(card)\n",
        "    def hand_size(self): \n",
        "        return len(self.hand)"
      ],
      "execution_count": 0,
      "outputs": []
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "rDUiupKA0Ay7",
        "colab_type": "code",
        "colab": {}
      },
      "source": [
        "# 33-3\n",
        "class CardDeck(object):\n",
        "    def __init__(self):\n",
        "        hearts = \"2H, 3H, 4H, 5H, 6H, 7H, 8H, 9H\"\n",
        "        diamonds = \"2D, 3D, 4D, 5D, 6D, 7D, 8D, 9D\"\n",
        "        spades = \"2S, 3S, 4S, 5S, 6S, 7S, 8S, 9S\"\n",
        "        clubs = \"2C, 3C, 4C, 5C, 6C, 7C, 8C, 9C\"\n",
        "        self.deck = hearts.split(', ')+diamonds.split(', ')+ \\\n",
        "                    spades.split(', ')+clubs.split(', ')"
      ],
      "execution_count": 0,
      "outputs": []
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "0Wy6EkuG0Awi",
        "colab_type": "code",
        "colab": {}
      },
      "source": [
        "# 33-4\n",
        "import random\n",
        "class CardDeck:\n",
        "    def __init__(self):\n",
        "        hearts = \"2H, 3H, 4H, 5H, 6H, 7H, 8H, 9H\"\n",
        "        diamonds = \"2D, 3D, 4D, 5D, 6D, 7D, 8D, 9D\"\n",
        "        spades = \"2S, 3S, 4S, 5S, 6S, 7S, 8S, 9S\"\n",
        "        clubs = \"2C, 3C, 4C, 5C, 6C, 7C, 8C, 9C\"\n",
        "        self.deck = hearts.split(', ')+diamonds.split(', ')\\\n",
        "                    + spades.split(', ')+clubs.split(', ')\n",
        "    def get_card(self):\n",
        "        if len(self.deck)< 1:\n",
        "            return None\n",
        "        card = random.choice(self.deck)\n",
        "        self.deck.remove(card)\n",
        "        return card\n",
        "    def compare_cards(self, card1, card2):\n",
        "        if card1[0] > card2[0]:\n",
        "            return card1\n",
        "        elif card1[0] < card2[0]:\n",
        "            return card2\n",
        "        elif card1[1] > card2[1]:\n",
        "            return card1\n",
        "        else:\n",
        "            return card2"
      ],
      "execution_count": 0,
      "outputs": []
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "su8WEZML0Aus",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 52
        },
        "outputId": "0635b362-92a3-42ea-ffec-087d15d87ae5"
      },
      "source": [
        "# 33-5\n",
        "name1 = input(\"What's your name? Player 1: \")\n",
        "player1 = Player(name1)\n",
        "name2 = input(\"What's your name? Player 2: \")\n",
        "player2 = Player(name2)\n",
        "deck = CardDeck()"
      ],
      "execution_count": 185,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "What's your name? Player 1: 蔡德龍\n",
            "What's your name? Player 2: 機器人1\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "Bzbepzer0AsP",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 710
        },
        "outputId": "4e5b3e54-9f3f-42ed-ef70-880e34bbff24"
      },
      "source": [
        "# 33-6\n",
        "name1 = input(\"What's your name? Player 1: \")\n",
        "player1 = Player(name1)\n",
        "name2 = input(\"What's your name? Player 2: \")\n",
        "player2 = Player(name2)\n",
        "deck = CardDeck()\n",
        "while True:\n",
        "    player1_card = deck.get_card()\n",
        "    player2_card = deck.get_card()\n",
        "    player1.add_card_to_hand(player1_card)\n",
        "    player2.add_card_to_hand(player2_card)\n",
        "    if player1_card == None or player2_card == None:\n",
        "        print(\"Game Over. No more cards in deck.\")\n",
        "        print(name1, \" has \", player1.hand_size())\n",
        "        print(name2, \" has \", player2.hand_size())\n",
        "        print(\"Who won?\")\n",
        "        if player1.hand_size()> player2.hand_size():\n",
        "            print(name2, \" wins!\")\n",
        "        elif player1.hand_size()< player2.hand_size():\n",
        "            print(name1, \" wins!\")\n",
        "        else:\n",
        "            print(\"A Tie!\") \n",
        "        break\n",
        "    else:\n",
        "        print(name1, \": \", player1_card)\n",
        "        print(name2, \": \", player2_card)\n",
        "    if deck.compare_cards(player1_card, player2_card) ==player1_card:\n",
        "        player2.add_card_to_hand(player1_card)\n",
        "        player1.remove_card_from_hand(player1_card)\n",
        "    else:\n",
        "        player1.add_card_to_hand(player2_card)\n",
        "        player2.remove_card_from_hand(player2_card)"
      ],
      "execution_count": 186,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "What's your name? Player 1: 蔡德龍\n",
            "What's your name? Player 2: 機器人2\n",
            "蔡德龍 :  8H\n",
            "機器人2 :  7D\n",
            "蔡德龍 :  5S\n",
            "機器人2 :  7C\n",
            "蔡德龍 :  7H\n",
            "機器人2 :  5C\n",
            "蔡德龍 :  4D\n",
            "機器人2 :  2S\n",
            "蔡德龍 :  8C\n",
            "機器人2 :  6H\n",
            "蔡德龍 :  4S\n",
            "機器人2 :  2C\n",
            "蔡德龍 :  6C\n",
            "機器人2 :  2H\n",
            "蔡德龍 :  5H\n",
            "機器人2 :  3S\n",
            "蔡德龍 :  3D\n",
            "機器人2 :  9C\n",
            "蔡德龍 :  9H\n",
            "機器人2 :  4H\n",
            "蔡德龍 :  5D\n",
            "機器人2 :  3H\n",
            "蔡德龍 :  3C\n",
            "機器人2 :  4C\n",
            "蔡德龍 :  6D\n",
            "機器人2 :  8S\n",
            "蔡德龍 :  9S\n",
            "機器人2 :  8D\n",
            "蔡德龍 :  9D\n",
            "機器人2 :  6S\n",
            "蔡德龍 :  7S\n",
            "機器人2 :  2D\n",
            "Game Over. No more cards in deck.\n",
            "蔡德龍  has  8\n",
            "機器人2  has  24\n",
            "Who won?\n",
            "蔡德龍  wins!\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "ElJIlUlI0Ann",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 87
        },
        "outputId": "51d4e62a-b240-42cb-eb83-c1eaa8802baf"
      },
      "source": [
        "# 34-1\n",
        "import math \n",
        "distance = float(input(\"How far away is your friend?(m)\"))\n",
        "speed = float(input(\"How fast can you throw?(m/s)\"))\n",
        "angle_d = float(input(\"What angle do you want to throw at?(degrees)\"))\n",
        "tolerance = 2 \n",
        "angle_r = math.radians(angle_d)\n",
        "reach = 2*speed**2*math.sin(angle_r)*math.cos(angle_r)/9.8\n",
        "if (reach > distance - tolerance)and (reach < distance + tolerance):\n",
        "    print(\"Nice throw!\")\n",
        "elif reach < distance - tolerance:\n",
        "    print(\"You didn't throw far enough.\")\n",
        "else:\n",
        "    print(\"You threw too far.\")"
      ],
      "execution_count": 187,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "How far away is your friend?(m)2\n",
            "How fast can you throw?(m/s)2\n",
            "What angle do you want to throw at?(degrees)2\n",
            "Nice throw!\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "t1RBbTqr0ffw",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 70
        },
        "outputId": "98892c13-17bb-484f-855b-69214ec8040f"
      },
      "source": [
        "# 34-2\n",
        "import random\n",
        "choice = input(\"Choose rock, paper, or scissors: \")\n",
        "r = random.random()\n",
        "if r < 1/3:\n",
        "    print(\"Computer chose rock.\")\n",
        "    if choice == \"paper\":\n",
        "        print(\"You win!\")\n",
        "    elif choice == \"scissors\":\n",
        "        print(\"You lose.\")\n",
        "    else:\n",
        "        print(\"Tie.\")\n",
        "elif 1/3 <= r < 2/3:\n",
        "    print(\"Computer chose paper.\")\n",
        "    if choice == \"scissors\":\n",
        "        print(\"You win!\")\n",
        "    elif choice == \"rock\":\n",
        "        print(\"You lose.\")\n",
        "    else:\n",
        "        print(\"Tie.\")\n",
        "else: \n",
        "    print(\"Computer chose scissors.\")\n",
        "    if choice == \"rock\":\n",
        "        print(\"You win!\")\n",
        "    elif choice == \"paper\":\n",
        "        print(\"You lose.\")\n",
        "    else:\n",
        "        print(\"Tie.\")"
      ],
      "execution_count": 188,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "Choose rock, paper, or scissors: 200\n",
            "Computer chose scissors.\n",
            "Tie.\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "GJcyK5790fc3",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 34
        },
        "outputId": "cda5baf9-170f-44fb-e08d-fbca250e4146"
      },
      "source": [
        "# 34-3\n",
        "import time\n",
        "start = time.time()\n",
        "count = 0\n",
        "for i in range(1000000):\n",
        "    count += 1\n",
        "end = time.time()\n",
        "print(end-start, \"seconds\")"
      ],
      "execution_count": 189,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "0.0965728759765625 seconds\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "v3X3BfwG0fao",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 366
        },
        "outputId": "4abf25dc-adbe-4a89-db8e-1784776622dc"
      },
      "source": [
        "# 35-1\n",
        "import tkinter\n",
        "window = tkinter.Tk()\n",
        "window.geometry(\"800x200\")\n",
        "window.title(\"My first GUI\")\n",
        "window.configure(background=\"grey\")\n",
        "window.mainloop()"
      ],
      "execution_count": 190,
      "outputs": [
        {
          "output_type": "error",
          "ename": "TclError",
          "evalue": "ignored",
          "traceback": [
            "\u001b[0;31m---------------------------------------------------------------------------\u001b[0m",
            "\u001b[0;31mTclError\u001b[0m                                  Traceback (most recent call last)",
            "\u001b[0;32m<ipython-input-190-096670dd5687>\u001b[0m in \u001b[0;36m<module>\u001b[0;34m()\u001b[0m\n\u001b[1;32m      1\u001b[0m \u001b[0;32mimport\u001b[0m \u001b[0mtkinter\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0;32m----> 2\u001b[0;31m \u001b[0mwindow\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0mtkinter\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mTk\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0m\u001b[1;32m      3\u001b[0m \u001b[0mwindow\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mgeometry\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;34m\"800x200\"\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m      4\u001b[0m \u001b[0mwindow\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mtitle\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;34m\"My first GUI\"\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m      5\u001b[0m \u001b[0mwindow\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mconfigure\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0mbackground\u001b[0m\u001b[0;34m=\u001b[0m\u001b[0;34m\"grey\"\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n",
            "\u001b[0;32m/usr/lib/python3.6/tkinter/__init__.py\u001b[0m in \u001b[0;36m__init__\u001b[0;34m(self, screenName, baseName, className, useTk, sync, use)\u001b[0m\n\u001b[1;32m   2021\u001b[0m                 \u001b[0mbaseName\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0mbaseName\u001b[0m \u001b[0;34m+\u001b[0m \u001b[0mext\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m   2022\u001b[0m         \u001b[0minteractive\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0;36m0\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0;32m-> 2023\u001b[0;31m         \u001b[0mself\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mtk\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0m_tkinter\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mcreate\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0mscreenName\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0mbaseName\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0mclassName\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0minteractive\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0mwantobjects\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0museTk\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0msync\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0muse\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0m\u001b[1;32m   2024\u001b[0m         \u001b[0;32mif\u001b[0m \u001b[0museTk\u001b[0m\u001b[0;34m:\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m   2025\u001b[0m             \u001b[0mself\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0m_loadtk\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n",
            "\u001b[0;31mTclError\u001b[0m: no display name and no $DISPLAY environment variable"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "52GrMD3q0fYH",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 366
        },
        "outputId": "d4e8b06e-f37c-4809-85d6-233ca1ed7cba"
      },
      "source": [
        "# 35-2\n",
        "import tkinter\n",
        "window = tkinter.Tk()\n",
        "window.geometry(\"800x200\")\n",
        "window.title(\"My first GUI\")\n",
        "window.configure(background=\"grey\")\n",
        "red = tkinter.Button(window, text=\"Red\", bg=\"red\")\n",
        "red.pack()\n",
        "yellow = tkinter.Button(window, text=\"Yellow\", bg=\"yellow\")\n",
        "yellow.pack()\n",
        "green = tkinter.Button(window, text=\"Green\", bg=\"green\")\n",
        "green.pack()\n",
        "textbox = tkinter.Entry(window)\n",
        "textbox.pack()\n",
        "colorlabel = tkinter.Label(window, height=\"10\", width=\"10\")\n",
        "colorlabel.pack()\n",
        "window.mainloop()"
      ],
      "execution_count": 191,
      "outputs": [
        {
          "output_type": "error",
          "ename": "TclError",
          "evalue": "ignored",
          "traceback": [
            "\u001b[0;31m---------------------------------------------------------------------------\u001b[0m",
            "\u001b[0;31mTclError\u001b[0m                                  Traceback (most recent call last)",
            "\u001b[0;32m<ipython-input-191-d4084aad062c>\u001b[0m in \u001b[0;36m<module>\u001b[0;34m()\u001b[0m\n\u001b[1;32m      1\u001b[0m \u001b[0;32mimport\u001b[0m \u001b[0mtkinter\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0;32m----> 2\u001b[0;31m \u001b[0mwindow\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0mtkinter\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mTk\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0m\u001b[1;32m      3\u001b[0m \u001b[0mwindow\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mgeometry\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;34m\"800x200\"\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m      4\u001b[0m \u001b[0mwindow\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mtitle\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;34m\"My first GUI\"\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m      5\u001b[0m \u001b[0mwindow\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mconfigure\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0mbackground\u001b[0m\u001b[0;34m=\u001b[0m\u001b[0;34m\"grey\"\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n",
            "\u001b[0;32m/usr/lib/python3.6/tkinter/__init__.py\u001b[0m in \u001b[0;36m__init__\u001b[0;34m(self, screenName, baseName, className, useTk, sync, use)\u001b[0m\n\u001b[1;32m   2021\u001b[0m                 \u001b[0mbaseName\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0mbaseName\u001b[0m \u001b[0;34m+\u001b[0m \u001b[0mext\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m   2022\u001b[0m         \u001b[0minteractive\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0;36m0\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0;32m-> 2023\u001b[0;31m         \u001b[0mself\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mtk\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0m_tkinter\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mcreate\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0mscreenName\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0mbaseName\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0mclassName\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0minteractive\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0mwantobjects\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0museTk\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0msync\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0muse\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0m\u001b[1;32m   2024\u001b[0m         \u001b[0;32mif\u001b[0m \u001b[0museTk\u001b[0m\u001b[0;34m:\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m   2025\u001b[0m             \u001b[0mself\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0m_loadtk\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n",
            "\u001b[0;31mTclError\u001b[0m: no display name and no $DISPLAY environment variable"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "qCL_CkRa0fVn",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 366
        },
        "outputId": "c6b8fdfd-d2d7-4821-cadc-cef21faafad2"
      },
      "source": [
        "# 35-3\n",
        "import tkinter\n",
        "def change_color(): \n",
        "    window.configure(background=\"white\")\n",
        "window = tkinter.Tk()\n",
        "window.geometry(\"800x200\")\n",
        "window.title(\"My first GUI\")\n",
        "window.configure(background=\"grey\")\n",
        "white = tkinter.Button(window, text=\"Click\", command=change_color)\n",
        "white.pack()\n",
        "window.mainloop()"
      ],
      "execution_count": 192,
      "outputs": [
        {
          "output_type": "error",
          "ename": "TclError",
          "evalue": "ignored",
          "traceback": [
            "\u001b[0;31m---------------------------------------------------------------------------\u001b[0m",
            "\u001b[0;31mTclError\u001b[0m                                  Traceback (most recent call last)",
            "\u001b[0;32m<ipython-input-192-66f9ce419306>\u001b[0m in \u001b[0;36m<module>\u001b[0;34m()\u001b[0m\n\u001b[1;32m      2\u001b[0m \u001b[0;32mdef\u001b[0m \u001b[0mchange_color\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m:\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m      3\u001b[0m     \u001b[0mwindow\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mconfigure\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0mbackground\u001b[0m\u001b[0;34m=\u001b[0m\u001b[0;34m\"white\"\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0;32m----> 4\u001b[0;31m \u001b[0mwindow\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0mtkinter\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mTk\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0m\u001b[1;32m      5\u001b[0m \u001b[0mwindow\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mgeometry\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;34m\"800x200\"\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m      6\u001b[0m \u001b[0mwindow\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mtitle\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;34m\"My first GUI\"\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n",
            "\u001b[0;32m/usr/lib/python3.6/tkinter/__init__.py\u001b[0m in \u001b[0;36m__init__\u001b[0;34m(self, screenName, baseName, className, useTk, sync, use)\u001b[0m\n\u001b[1;32m   2021\u001b[0m                 \u001b[0mbaseName\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0mbaseName\u001b[0m \u001b[0;34m+\u001b[0m \u001b[0mext\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m   2022\u001b[0m         \u001b[0minteractive\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0;36m0\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0;32m-> 2023\u001b[0;31m         \u001b[0mself\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mtk\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0m_tkinter\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mcreate\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0mscreenName\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0mbaseName\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0mclassName\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0minteractive\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0mwantobjects\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0museTk\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0msync\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0muse\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0m\u001b[1;32m   2024\u001b[0m         \u001b[0;32mif\u001b[0m \u001b[0museTk\u001b[0m\u001b[0;34m:\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m   2025\u001b[0m             \u001b[0mself\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0m_loadtk\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n",
            "\u001b[0;31mTclError\u001b[0m: no display name and no $DISPLAY environment variable"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "fphZhqSF0fTP",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 366
        },
        "outputId": "6cdb6a64-081d-4b80-e62a-24698182b460"
      },
      "source": [
        "# 35-4\n",
        "import tkinter\n",
        "import time \n",
        "def countdown(): \n",
        "    countlabel.configure(background=\"white\")\n",
        "    howlong = int(textbox.get()) \n",
        "    for i in range(howlong, 0, -1):\n",
        "        countlabel.configure(text=i)\n",
        "        window.update()\n",
        "        time.sleep(1) \n",
        "    countlabel.configure(text=\"DONE!\") \n",
        "window = tkinter.Tk()\n",
        "window.geometry(\"800x600\")\n",
        "window.title(\"My first GUI\")\n",
        "window.configure(background=\"grey\")\n",
        "lbl=tkinter.Label(window,text=\"How many seconds to count down?\")\n",
        "lbl.pack()\n",
        "textbox = tkinter.Entry(window) \n",
        "textbox.pack()\n",
        "count = tkinter.Button(window, text=\"Countdown!\",command=countdown) \n",
        "count.pack()\n",
        "countlabel = tkinter.Label(window, height=\"10\", width=\"10\")\n",
        "countlabel.pack()\n",
        "window.mainloop()"
      ],
      "execution_count": 193,
      "outputs": [
        {
          "output_type": "error",
          "ename": "TclError",
          "evalue": "ignored",
          "traceback": [
            "\u001b[0;31m---------------------------------------------------------------------------\u001b[0m",
            "\u001b[0;31mTclError\u001b[0m                                  Traceback (most recent call last)",
            "\u001b[0;32m<ipython-input-193-4f2750fbb3e8>\u001b[0m in \u001b[0;36m<module>\u001b[0;34m()\u001b[0m\n\u001b[1;32m      9\u001b[0m         \u001b[0mtime\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0msleep\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;36m1\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m     10\u001b[0m     \u001b[0mcountlabel\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mconfigure\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0mtext\u001b[0m\u001b[0;34m=\u001b[0m\u001b[0;34m\"DONE!\"\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0;32m---> 11\u001b[0;31m \u001b[0mwindow\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0mtkinter\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mTk\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0m\u001b[1;32m     12\u001b[0m \u001b[0mwindow\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mgeometry\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;34m\"800x600\"\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m     13\u001b[0m \u001b[0mwindow\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mtitle\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;34m\"My first GUI\"\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n",
            "\u001b[0;32m/usr/lib/python3.6/tkinter/__init__.py\u001b[0m in \u001b[0;36m__init__\u001b[0;34m(self, screenName, baseName, className, useTk, sync, use)\u001b[0m\n\u001b[1;32m   2021\u001b[0m                 \u001b[0mbaseName\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0mbaseName\u001b[0m \u001b[0;34m+\u001b[0m \u001b[0mext\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m   2022\u001b[0m         \u001b[0minteractive\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0;36m0\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0;32m-> 2023\u001b[0;31m         \u001b[0mself\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mtk\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0m_tkinter\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mcreate\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0mscreenName\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0mbaseName\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0mclassName\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0minteractive\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0mwantobjects\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0museTk\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0msync\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0muse\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0m\u001b[1;32m   2024\u001b[0m         \u001b[0;32mif\u001b[0m \u001b[0museTk\u001b[0m\u001b[0;34m:\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m   2025\u001b[0m             \u001b[0mself\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0m_loadtk\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n",
            "\u001b[0;31mTclError\u001b[0m: no display name and no $DISPLAY environment variable"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "vQ2TlCgR0rJw",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 366
        },
        "outputId": "4e6215e2-eaae-40fe-8565-fd025d312387"
      },
      "source": [
        "# 36-1\n",
        "import tkinter\n",
        "window = tkinter.Tk()\n",
        "window.geometry(\"800x800\")\n",
        "window.title(\"Tag!\")\n",
        "canvas = tkinter.Canvas(window)\n",
        "canvas.pack(expand=1, fill='both')\n",
        "window.mainloop()"
      ],
      "execution_count": 194,
      "outputs": [
        {
          "output_type": "error",
          "ename": "TclError",
          "evalue": "ignored",
          "traceback": [
            "\u001b[0;31m---------------------------------------------------------------------------\u001b[0m",
            "\u001b[0;31mTclError\u001b[0m                                  Traceback (most recent call last)",
            "\u001b[0;32m<ipython-input-194-dbecc521c19b>\u001b[0m in \u001b[0;36m<module>\u001b[0;34m()\u001b[0m\n\u001b[1;32m      1\u001b[0m \u001b[0;32mimport\u001b[0m \u001b[0mtkinter\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0;32m----> 2\u001b[0;31m \u001b[0mwindow\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0mtkinter\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mTk\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0m\u001b[1;32m      3\u001b[0m \u001b[0mwindow\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mgeometry\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;34m\"800x800\"\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m      4\u001b[0m \u001b[0mwindow\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mtitle\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;34m\"Tag!\"\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m      5\u001b[0m \u001b[0mcanvas\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0mtkinter\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mCanvas\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0mwindow\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n",
            "\u001b[0;32m/usr/lib/python3.6/tkinter/__init__.py\u001b[0m in \u001b[0;36m__init__\u001b[0;34m(self, screenName, baseName, className, useTk, sync, use)\u001b[0m\n\u001b[1;32m   2021\u001b[0m                 \u001b[0mbaseName\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0mbaseName\u001b[0m \u001b[0;34m+\u001b[0m \u001b[0mext\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m   2022\u001b[0m         \u001b[0minteractive\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0;36m0\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0;32m-> 2023\u001b[0;31m         \u001b[0mself\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mtk\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0m_tkinter\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mcreate\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0mscreenName\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0mbaseName\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0mclassName\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0minteractive\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0mwantobjects\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0museTk\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0msync\u001b[0m\u001b[0;34m,\u001b[0m \u001b[0muse\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0m\u001b[1;32m   2024\u001b[0m         \u001b[0;32mif\u001b[0m \u001b[0museTk\u001b[0m\u001b[0;34m:\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m   2025\u001b[0m             \u001b[0mself\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0m_loadtk\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n",
            "\u001b[0;31mTclError\u001b[0m: no display name and no $DISPLAY environment variable"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "vVoHFA9W0t_P",
        "colab_type": "code",
        "colab": {}
      },
      "source": [
        "# 36-2\n",
        "import random\n",
        "class Player():\n",
        "    def __init__(self, canvas, color):\n",
        "        side = random.randint(1, 100)\n",
        "        x1 = random.randint(0, 700)\n",
        "        y1 = random.randint(0, 700)\n",
        "        x2 = x1+side\n",
        "        y2 = y1+side\n",
        "        self.color = color\n",
        "        self.coords = [x1, y1, x2, y2]\n",
        "        self.piece = canvas.create_rectangle(self.coords,fill= self.color)"
      ],
      "execution_count": 0,
      "outputs": []
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "dCQT7xkq0rLf",
        "colab_type": "code",
        "colab": {}
      },
      "source": [
        "# 36-3\n",
        "class Player():\n",
        "    def __init__(self, canvas, color):\n",
        "        size = random.randint(1, 100)\n",
        "        x1 = random.randint(100, 700)\n",
        "        y1 = random.randint(100, 700)\n",
        "        x2 = x1+side\n",
        "        y2 = y1+side\n",
        "        self.color = color\n",
        "        self.coords = [x1, y1, x2, y2]\n",
        "        self.piece = canvas.create_rectangle(self.coords,fill=self.color)\n",
        "    def move(self, direction):\n",
        "        if direction == 'u':\n",
        "            self.coords[1] -= 10\n",
        "            self.coords[3] -= 10\n",
        "            canvas.coords(self.piece, self.coords)\n",
        "        if direction == 'd':\n",
        "            self.coords[1] += 10\n",
        "            self.coords[3] += 10\n",
        "            canvas.coords(self.piece, self.coords) \n",
        "        if direction == 'l':\n",
        "            self.coords[0] -= 10\n",
        "            self.coords[2] -= 10\n",
        "            canvas.coords(self.piece, self.coords)\n",
        "        if direction == 'r':\n",
        "            self.coords[0] += 10\n",
        "            self.coords[2] += 10\n",
        "            canvas.coords(self.piece, self.coords)"
      ],
      "execution_count": 0,
      "outputs": []
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "ieD3MrQD0rG-",
        "colab_type": "code",
        "colab": {}
      },
      "source": [
        "# 36-4\n",
        "def handle_key(event):\n",
        "    if event.char == 'w' :\n",
        "        player1.move('u')\n",
        "    if event.char == 's' :\n",
        "        player1.move('d')\n",
        "    if event.char == 'a' :\n",
        "        player1.move('l')\n",
        "    if event.char == 'd' :\n",
        "        player1.move('r')\n",
        "    if event.char == 'i' :\n",
        "        player2.move('u')\n",
        "    if event.char == 'k' :\n",
        "        player2.move('d')\n",
        "    if event.char == 'j' :\n",
        "        player2.move('l')\n",
        "    if event.char == 'l' :\n",
        "        player2.move('r')"
      ],
      "execution_count": 0,
      "outputs": []
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "r3WNmYXf0rEj",
        "colab_type": "code",
        "colab": {}
      },
      "source": [
        "# 36-5\n",
        "def handle_key(event):\n",
        "    if event.char == 'w' :\n",
        "        player1.move('u')\n",
        "    if event.char == 's' :\n",
        "        player1.move('d')\n",
        "    if event.char == 'a' :\n",
        "        player1.move('l')\n",
        "    if event.char == 'd' :\n",
        "        player1.move('r')\n",
        "    if event.char == 'i' :\n",
        "        player2.move('u')\n",
        "    if event.char == 'k' :\n",
        "        player2.move('d')\n",
        "    if event.char == 'j' :\n",
        "        player2.move('l')\n",
        "    if event.char == 'l' :\n",
        "        player2.move('r')\n",
        "    yellow_xy = canvas.bbox(1)\n",
        "    overlapping = canvas.find_overlapping(yellow_xy[0], yellow_xy[1], yellow_xy[2], yellow_xy[3])\n",
        "    if 2 in overlapping:\n",
        "        canvas.create_text(100, 100, font=(\"Arial\", 20), text=\"Tag!\")"
      ],
      "execution_count": 0,
      "outputs": []
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "FjBmpa5R00o5",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 331
        },
        "outputId": "16a68aa3-1051-4f75-8a47-d5a944d5d468"
      },
      "source": [
        "# 37-1\n",
        "import unittest\n",
        "class TestMyCode(unittest.TestCase):\n",
        "    def test_addition_2_2(self):\n",
        "        self.assertEqual(2+2, 4)\n",
        "    def test_subtraction_2_2(self):\n",
        "        self.assertNotEqual(2-2, 4)\n",
        "unittest.main()"
      ],
      "execution_count": 199,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "E\n",
            "======================================================================\n",
            "ERROR: /root/ (unittest.loader._FailedTest)\n",
            "----------------------------------------------------------------------\n",
            "AttributeError: module '__main__' has no attribute '/root/'\n",
            "\n",
            "----------------------------------------------------------------------\n",
            "Ran 1 test in 0.002s\n",
            "\n",
            "FAILED (errors=1)\n"
          ],
          "name": "stderr"
        },
        {
          "output_type": "error",
          "ename": "SystemExit",
          "evalue": "ignored",
          "traceback": [
            "An exception has occurred, use %tb to see the full traceback.\n",
            "\u001b[0;31mSystemExit\u001b[0m\u001b[0;31m:\u001b[0m True\n"
          ]
        },
        {
          "output_type": "stream",
          "text": [
            "/usr/local/lib/python3.6/dist-packages/IPython/core/interactiveshell.py:2890: UserWarning: To exit: use 'exit', 'quit', or Ctrl-D.\n",
            "  warn(\"To exit: use 'exit', 'quit', or Ctrl-D.\", stacklevel=1)\n"
          ],
          "name": "stderr"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "EJd8mWVo0rCW",
        "colab_type": "code",
        "colab": {}
      },
      "source": [
        "# 37-2\n",
        "def is_prime(n):\n",
        "    prime = True\n",
        "    for i in range(1, n):\n",
        "        if n%i == 0:\n",
        "            prime = False\n",
        "    return prime\n",
        "def absolute_value(n):\n",
        "    if n < 0:\n",
        "        return n\n",
        "    elif n > 0:\n",
        "        return n"
      ],
      "execution_count": 0,
      "outputs": []
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "AWyvuiIz0rAP",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 384
        },
        "outputId": "7182fa31-7e27-4892-ad5c-2b4190787f46"
      },
      "source": [
        "# 37-3\n",
        "import unittest\n",
        "import funcs\n",
        "class TestPrime(unittest.TestCase):\n",
        "    def test_prime_5(self):\n",
        "        isprime = funcs.is_prime(5)\n",
        "        self.assertEqual(isprime, True)\n",
        "    def test_prime_4(self):\n",
        "        isprime = funcs.is_prime(4)\n",
        "        self.assertEqual(isprime, False)\n",
        "    def test_prime_10000(self):\n",
        "        isprime = funcs.is_prime(10000)\n",
        "        self.assertEqual(isprime, False)\n",
        "class TestAbs(unittest.TestCase):\n",
        "    def test_abs_5(self):\n",
        "        absolute = funcs.absolute_value(5)\n",
        "        self.assertEqual(absolute, 5)\n",
        "    def test_abs_neg5(self):\n",
        "        absolute = funcs.absolute_value(-5)\n",
        "        self.assertEqual(absolute, 5)\n",
        "    def test_abs_0(self):\n",
        "        absolute = funcs.absolute_value(0)\n",
        "        self.assertEqual(absolute, 0)\n",
        "unittest.main()      "
      ],
      "execution_count": 201,
      "outputs": [
        {
          "output_type": "error",
          "ename": "ModuleNotFoundError",
          "evalue": "ignored",
          "traceback": [
            "\u001b[0;31m---------------------------------------------------------------------------\u001b[0m",
            "\u001b[0;31mModuleNotFoundError\u001b[0m                       Traceback (most recent call last)",
            "\u001b[0;32m<ipython-input-201-85196dd8bb48>\u001b[0m in \u001b[0;36m<module>\u001b[0;34m()\u001b[0m\n\u001b[1;32m      1\u001b[0m \u001b[0;32mimport\u001b[0m \u001b[0munittest\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0;32m----> 2\u001b[0;31m \u001b[0;32mimport\u001b[0m \u001b[0mfuncs\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0m\u001b[1;32m      3\u001b[0m \u001b[0;32mclass\u001b[0m \u001b[0mTestPrime\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0munittest\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mTestCase\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m:\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m      4\u001b[0m     \u001b[0;32mdef\u001b[0m \u001b[0mtest_prime_5\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0mself\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m:\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m      5\u001b[0m         \u001b[0misprime\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0mfuncs\u001b[0m\u001b[0;34m.\u001b[0m\u001b[0mis_prime\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;36m5\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n",
            "\u001b[0;31mModuleNotFoundError\u001b[0m: No module named 'funcs'",
            "",
            "\u001b[0;31m---------------------------------------------------------------------------\u001b[0;32m\nNOTE: If your import is failing due to a missing package, you can\nmanually install dependencies using either !pip or !apt.\n\nTo view examples of installing some common dependencies, click the\n\"Open Examples\" button below.\n\u001b[0;31m---------------------------------------------------------------------------\u001b[0m\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "qgjCssdx04V3",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 135
        },
        "outputId": "591a0b3c-8bce-4bbb-d5ab-9533f74f75b0"
      },
      "source": [
        "# A-2\n",
        "class Fraction:\n",
        "    def __init__(self, top, bottom):\n",
        "        self.top = top \n",
        "        self.bottom = bottom\n",
        "    def __add__(self, other_fraction):\n",
        "        new_top = self.top*other_fraction.bottom + \\ self.bottom*other_fraction.top\n",
        "        new_bottom = self.bottom*other_fraction.bottom\n",
        "        return Fraction(new_top, new_bottom)\n",
        "    def __mul__(self, other_fraction):\n",
        "        new_top = self.top*other_fraction.top\n",
        "        new_bottom = self.bottom*other_fraction.bottom\n",
        "        return Fraction(new_top, new_bottom)"
      ],
      "execution_count": 202,
      "outputs": [
        {
          "output_type": "error",
          "ename": "SyntaxError",
          "evalue": "ignored",
          "traceback": [
            "\u001b[0;36m  File \u001b[0;32m\"<ipython-input-202-a381d92e916c>\"\u001b[0;36m, line \u001b[0;32m6\u001b[0m\n\u001b[0;31m    new_top = self.top*other_fraction.bottom + \\ self.bottom*other_fraction.top\u001b[0m\n\u001b[0m                                                                               ^\u001b[0m\n\u001b[0;31mSyntaxError\u001b[0m\u001b[0;31m:\u001b[0m unexpected character after line continuation character\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "VbE3ox1M04al",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 135
        },
        "outputId": "bf580f30-dd9f-4ab4-da8a-cac58c76a9cc"
      },
      "source": [
        "# A-3\n",
        "class Fraction:\n",
        "    def __init__(self, top, bottom):\n",
        "        self.top = top \n",
        "        self.bottom = bottom\n",
        "    def __add__(self, other_fraction):\n",
        "        new_top = self.top*other_fraction.bottom + \\ self.bottom*other_fraction.top\n",
        "        new_bottom = self.bottom*other_fraction.bottom\n",
        "        return Fraction(new_top, new_bottom)\n",
        "    def __mul__(self, other_fraction):\n",
        "        new_top = self.top*other_fraction.top\n",
        "        new_bottom = self.bottom*other_fraction.bottom\n",
        "        return Fraction(new_top, new_bottom)\n",
        "    def __str__(self):\n",
        "        return str(self.top)+\"/\"+str(self.bottom)"
      ],
      "execution_count": 203,
      "outputs": [
        {
          "output_type": "error",
          "ename": "SyntaxError",
          "evalue": "ignored",
          "traceback": [
            "\u001b[0;36m  File \u001b[0;32m\"<ipython-input-203-b62c0d9c77ca>\"\u001b[0;36m, line \u001b[0;32m6\u001b[0m\n\u001b[0;31m    new_top = self.top*other_fraction.bottom + \\ self.bottom*other_fraction.top\u001b[0m\n\u001b[0m                                                                               ^\u001b[0m\n\u001b[0;31mSyntaxError\u001b[0m\u001b[0;31m:\u001b[0m unexpected character after line continuation character\n"
          ]
        }
      ]
    }
  ]
}
