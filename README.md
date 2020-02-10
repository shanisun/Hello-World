public class Time {
	public static void main(String[] args) {
		int count = 0;
		for (int i = 0; i < 24; i++) {
			for (int j = 0; j < 60; j++) { //You can replace j < 24
				if (i == j) {
					System.out.println("Found - " + String.format("%02d", i) + ":" + String.format("%02d", j));
					count++;
				}
			}
		}

		System.out.println("Total found " + count);
	}
}
