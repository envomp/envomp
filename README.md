``` Java
import java.util.Random;

public class HelloWorld {
	public static void main(String... args) {
		System.out.println(randomString(-229985452) + ' ' + randomString(-147909649));
	}

	public static String randomString(int seed) {
		Random rand = new Random(seed);
		StringBuilder sb = new StringBuilder();
		while (true) {
			int n = rand.nextInt(27);
			if (n == 0) {
				break;
			}
			sb.append((char) ('`' + n));
		}
		return sb.toString();
	}
}
```

<details>
  <summary>CV</summary>
  <img align="left" alt="CV" src="enrico_vompa_cv.png" />
</details>

<details>
  <summary>Github stats</summary>
  <img align="left" alt="Github stats" src="https://github-readme-stats.codestackr.vercel.app/api?username=envomp&show_icons=true&hide_border=true&include_all_commits=true" />
</details>
