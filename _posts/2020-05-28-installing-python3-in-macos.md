---
title:  "Installing Python3 in macOS [Dummy]"
date:   2020-05-28
tags: ["#python3", "#installation"]
---
Starting from Mac Os Catalina, Python2 & Python3 is installed by default in macos. You can check by entering `python3 --version` command in Terminal.

![woman in pink tank top and blue denim jeans standing near window](https://images.unsplash.com/photo-1588417722655-5dc464048a97?ixlib=rb-1.2.1&q=80&fm=jpg&crop=entropy&cs=tinysrgb&w=1080&fit=max&ixid=eyJhcHBfaWQiOjkwODQwfQ)

Now Enter `python2 --version` to see version.

![man sitting on ground beside parked silver cruiser motorcycle](https://images.unsplash.com/photo-1558981852-426c6c22a060?ixlib=rb-1.2.1&q=80&fm=jpg&crop=entropy&cs=tinysrgb&w=1080&fit=max&ixid=eyJhcHBfaWQiOjkwODQwfQ)

## Installing pip
But there's no pip installed by default. You need to install pip by downloading and running get-pip.py.

 * Download [get-pip.py](https://bootstrap.pypa.io/get-pip.py) file.
 * Go to the directory where get-pip.py file exists and execute file by entering `python3 get-pip.py`.
 * You can check installation by entering `pip --version`.

> Note: Open new terminal window to check pip installation.

Yay! You've now configured how to start with python. 

---
## Printing Fibonacci series
Let's see how we can print *fibonacci series* using java.

    public class Fibonacci {
    
        public static void main(String[] args) {
    
            int n = 10, t1 = 0, t2 = 1;
            System.out.print("First " + n + " terms: ");
    
            for (int i = 1; i <= n; ++i)
            {
                System.out.print(t1 + " + ");
    
                int sum = t1 + t2;
                t1 = t2;
                t2 = sum;
            }
        }
    }

It produces the following output

    0 + 1 + 1 + 2 + 3 + 5 + 8 + 13 + 21 + 34 +

<p>I will display &#128533;</p>
