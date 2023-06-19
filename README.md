class MyProfile extends StatelessWidget {
  final String username;
  final int age;
  final String collaborations;
  final String learning;

  const MyProfile({
    super.key,
    required this.username,
    required this.age,
    required this.collaborations,
    required this.learning,
  });
  @override
  Widget build(BuildContext context) {
    return const Column(
      children: [
        MyProfile(
          username: '@kalaqic',
          age: 18,
          collaborations: 'CaoCao',
          learning: 'how to live properly :D',
        )
      ],
    );
  }
}
<!---
kalaqic/kalaqic is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
