import React from "react";

export default function PortfolioPage() {
  return (
    <div className="min-h-screen bg-white text-gray-800 font-sans">
      {/* Navbar */}
      <nav className="bg-indigo-700 border-b border-indigo-500">
        <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
          <div className="flex h-16 items-center justify-between">
            <div className="flex items-center">
              <span className="text-white text-2xl font-bold">Divya Portfolio</span>
            </div>
            <div className="space-x-4">
              <a href="#" className="text-white hover:bg-indigo-600 px-3 py-2 rounded-md">Home</a>
              <a href="#projects" className="text-white hover:bg-indigo-600 px-3 py-2 rounded-md">Projects</a>
              <a href="#contact" className="text-white hover:bg-indigo-600 px-3 py-2 rounded-md">Contact</a>
            </div>
          </div>
        </div>
      </nav>

      {/* Hero */}
      <section className="bg-indigo-700 py-20">
        <div className="max-w-4xl mx-auto text-center px-4">
          <h1 className="text-5xl font-extrabold text-white">Hi, I'm Moguloju Divya</h1>
          <p className="text-xl text-indigo-100 mt-4">
            Software Developer | Python | Machine Learning | AI Enthusiast
          </p>
        </div>
      </section>

      {/* About */}
      <section className="py-12 bg-blue-50">
        <div className="max-w-4xl mx-auto px-4">
          <h2 className="text-3xl font-bold text-indigo-700 mb-4">Objective</h2>
          <p className="text-gray-700 text-lg">
            To obtain a position in the computer science field where I can utilize my programming,
            problem-solving, and critical thinking skills to develop innovative software solutions while
            growing professionally in a collaborative environment.
          </p>
        </div>
      </section>

      {/* Education */}
      <section className="py-12">
        <div className="max-w-4xl mx-auto px-4">
          <h2 className="text-3xl font-bold text-indigo-700 mb-4">Education</h2>
          <ul className="list-disc pl-6 text-lg text-gray-800">
            <li><strong>Auburn University at Montgomery</strong> — M.S. in Computer Science (2024 - Pursuing)</li>
            <li><strong>Avanthi Institute of Engineering and Technology</strong> — B.Tech in CSE (2018 - 2022)</li>
          </ul>
        </div>
      </section>

      {/* Experience */}
      <section className="py-12 bg-blue-50">
        <div className="max-w-4xl mx-auto px-4">
          <h2 className="text-3xl font-bold text-indigo-700 mb-4">Experience</h2>
          <div className="bg-white shadow-md p-6 rounded-lg">
            <h3 className="text-xl font-bold text-indigo-600">Cloud Technologies – Intern</h3>
            <p className="text-sm text-gray-500 mb-3">Sept 2022 – Feb 2023</p>
            <ul className="list-disc pl-5 space-y-1 text-gray-700">
              <li>Managed employee records and information flow.</li>
              <li>Helped develop employee management software.</li>
              <li>Optimized cloud storage for personnel data.</li>
              <li>Improved data security and accuracy.</li>
            </ul>
          </div>
        </div>
      </section>

      {/* Projects */}
      <section id="projects" className="py-12">
        <div className="max-w-4xl mx-auto px-4">
          <h2 className="text-3xl font-bold text-indigo-700 mb-6">Projects</h2>
          <div className="grid gap-6">
            <div className="bg-white border border-indigo-100 p-6 rounded-lg shadow">
              <h3 className="text-xl font-semibold text-indigo-600">Automatic Number Plate Recognition</h3>
              <p className="text-gray-700 mt-2">Used image processing to detect vehicle number plates and extract data using ML algorithms.</p>
            </div>
            <div className="bg-white border border-indigo-100 p-6 rounded-lg shadow">
              <h3 className="text-xl font-semibold text-indigo-600">Detecting Fake Statements using AI</h3>
              <p className="text-gray-700 mt-2">Built an AI model to verify public statements using language pattern analysis and data validation.</p>
            </div>
          </div>
        </div>
      </section>

      {/* Skills */}
      <section className="py-12 bg-blue-50">
        <div className="max-w-4xl mx-auto px-4">
          <h2 className="text-3xl font-bold text-indigo-700 mb-4">Skills & Certifications</h2>
          <ul className="list-disc pl-6 space-y-1 text-gray-800 text-lg">
            <li><strong>Languages:</strong> C, C++, Python, HTML</li>
            <li><strong>Tools:</strong> Microsoft Office</li>
            <li><strong>Certifications:</strong> Python (Udemy), Ethical Hacking (Wireshark), Elements of AI (Minna Learn)</li>
          </ul>
        </div>
      </section>

      {/* Contact */}
      <section id="contact" className="py-12">
        <div className="max-w-4xl mx-auto px-4 text-center">
          <h2 className="text-3xl font-bold text-indigo-700 mb-2">Get in Touch</h2>
          <p className="text-gray-600 text-lg">Email: <a href="mailto:mogulojudivya16@gmail.com" className="text-indigo-500 hover:underline">mogulojudivya16@gmail.com</a></p>
          <p className="text-gray-600 text-lg">Phone: +1 (334) 498-2416</p>
        </div>
      </section>

      {/* Footer */}
      <footer className="bg-indigo-700 text-white text-center py-4">
        © 2025 Moguloju Divya. All rights reserved.
      </footer>
    </div>
  );
}
