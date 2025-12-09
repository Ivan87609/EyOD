# EyOD
public static void main(String[] args) {
       int size = 1_000_000;
        int[] data = new int[size];
        Random random = new Random()
        for (int i = 0; i < size; i++) {
            data[i] = random.nextInt(1_000_000);
        }
        long start = System.currentTimeMillis();
        Arrays.sort(data);
        long end = System.currentTimeMillis();
       System.out.println("QuickSort (Arrays.sort) terminó en: " + (end - start) + " ms");
    }
}


















