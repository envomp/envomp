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
  <summary>Masters Thesis on Data Lakehouse Architecture</summary>
  <p><a href="https://digikogu.taltech.ee/en/Item/472b9cba-f80b-49d2-81af-2f59eed03f16">Hyperlink to TalTech digital library</a></p>
</details>
