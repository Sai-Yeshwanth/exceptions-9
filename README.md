class Jala {
	public static void main(String[] args) {
		int a[] = { 3, 5, 6, 7 };
		try {
			for (int i = 0; i <= 4; i++) {
				System.out.println(a[i]);
			}
		} catch (ArrayIndexOutOfBoundsException ae) {
			System.out.println("Max number of elements in array is 4 : " + ae);
		} finally {
			System.out.println("Byeee!!!!");
		}
	}
}
