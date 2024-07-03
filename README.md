import 'package:flutter/material.dart';

class AboutPage extends StatelessWidget {
  const AboutPage({super.key});

  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(
        title: Text(
          "Tentang Aplikasi",
          style: TextStyle(
            fontWeight: FontWeight.bold,
          ),
        ),
      ),
      body: Padding(
        padding: const EdgeInsets.all(16.0),
        child: Column(
          crossAxisAlignment: CrossAxisAlignment.start,
          children: [
            Text(
              "Tentang Aplikasi Ini",
              style: TextStyle(
                fontSize: 24,
                fontWeight: FontWeight.bold,
              ),
            ),
            SizedBox(height: 10),
            Text(
              "Aplikasi ini dirancang untuk memberikan pengalaman yang efisien dan ramah pengguna dalam mengelola tugas Anda.",
              style: TextStyle(
                fontSize: 16,
              ),
            ),
            SizedBox(height: 20),
            Text(
              "Biodata Pengembang",
              style: TextStyle(
                fontSize: 24,
                fontWeight: FontWeight.bold,
              ),
            ),
            SizedBox(height: 10),
            Text(
              "Nama: Dea NUrul Hoeriah",
              style: TextStyle(
                fontSize: 16,
              ),
            ),
            SizedBox(height: 5),
            Text(
              "Email: 2106070@itg.ac.id",
              style: TextStyle(
                fontSize: 16,
              ),
            ),
            SizedBox(height: 5),
            Text(
              "Institusi: Institut Teknologi Garut",
              style: TextStyle(
                fontSize: 16,
              ),
            ),
            SizedBox(height: 20),
            Center(
              child: Text(
                "itg.ac.id © 2024",
                style: TextStyle(
                  fontWeight: FontWeight.bold,
                  fontSize: 16,
                ),
              ),
            ),
          ],
        ),
      ),
    );
  }
}
