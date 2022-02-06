### Hola! I am Zunaid! 👋

 <img align="right" alt="IMG" src="https://github.com/zedunaid/zedunaid/blob/main/Zunaid_GH_Profile.jpeg"  width="300" />

![visitors](https://estruyf-github.azurewebsites.net/api/VisitorHit?user=zedunaid&repo=zedunaid&countColor=%237B1E7A)

🎓 Master Of Computer Science at [NCSU](https://www.ncsu.edu).

🚀 Bachelor of Computer Engineering at [KJSCE](https://somaiya.kjsce.com).

## About Me 🥳
- 📍  I'm from Gondia,MH 🇮🇳. Currently living in Raleigh, NC 🇺🇸  
- 🌱  I’m currently learning DevOps, CI/CD, PyTorch, Spark and Kafka 
- 👯  I’m looking to contribute on open source softwares that can change lives. 
- 💬  Contact me if you've amazing software engineering opportunities for Summer 2022.

## Skills and Tools 🤹🏻‍♂️:
<img align="left" alt="Java" width="30px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/java/java.png" />
<img align="left" alt="Java" width="30px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/android/android.png" />
<img align="left" alt="Java" width="30px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/csharp/csharp.png" />
<img align="left" alt="Java" width="30px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/dotnet/dotnet.png" />
<img align="left" alt="React" width="30px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/react/react.png" />
<img align="left" alt="Node.js" width="30px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/nodejs/nodejs.png" />
<img align="left" alt="MongoDB" width="30px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/mongodb/mongodb.png" />
<img align="left" alt="python" width="30px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/python/python.png" />
<img align="left" alt="SQL" width="30px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/sql/sql.png" />
<img align="left" alt="postgreSQL" width="30px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/postgresql/postgresql.png" />
<img align="left" alt="Git" width="30px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/git/git.png" />
<img align="left" alt="Docker" width="30px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/docker/docker.png" />
<br/>
<br />

## Favorite Code Snippet 🪄:
 **Problem Statement:**
Tower of Hanoi is a mathematical puzzle where we have three rods and n disks. The objective of the puzzle is to move the entire stack to another rod, obeying the following simple rules: 

- Only one disk can be moved at a time.
- Each move consists of taking the upper disk from one of the stacks and placing it on top of another stack i.e. a disk can only be moved if it is the uppermost disk on a stack.
- No disk may be placed on top of a smaller disk.
- Source: [GeeksForGeeks](https://www.geeksforgeeks.org/c-program-for-tower-of-hanoi/)

**With the magic of recursion, we can solve this complex mathematical puzzle within few lines of code. 🥶** 
``` java
public class TowerOfHanoi {
    static int count = 0;
    public static void main(String args[]) {
        String source = "A";
        String destination="C";
        String helper="B";
        solveTOH(3,source,destination,helper);
        System.out.println("No of Steps: "+count);
    }
    public static void solveTOH(int n, String source, String destination, String helper) {
        count ++;
        if(n==1) {
            System.out.println("Moving plate "+n+" from "+source+" to "+destination);
            return;
        }
        solveTOH(n-1,source,helper,destination);
        System.out.println("Moving plate "+n+" from "+source+" to "+destination);
        solveTOH(n-1,helper,destination,source);
        return;
    }
} 
```
<br />

---

<details>
  <summary>:zap: GitHub Stats</summary>

  <img align="left" alt="Zunaid's GitHub Stats" src="https://github-readme-stats.vercel.app/api?username=zedunaid&show_icons=true&hide_border=true&theme=tokyonight" />

</details>


<details>
  <summary>:zap: Most Used Language</summary>

  <img align="left" alt="Zunaid's GitHub Top Languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=zedunaid&layout=compact" />

</details>

### Connect with me on LinkedIn:
[<img align="left" alt="zhsorath | LinkedIn" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" />][linkedin]


[linkedin]: https://www.linkedin.com/in/zunaid-sorathiya-2a91bb146/
