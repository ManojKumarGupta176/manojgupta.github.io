export default function AcademicPortfolio() {
  return (
    <div className="min-h-screen bg-gray-50 text-gray-800 font-sans">
      {/* Header */}
      <header className="bg-blue-900 text-white py-16 px-6 text-center shadow-lg">
       
        <h1 className="text-4xl font-bold mt-6">Manoj Kumar Gupta</h1>
        <p className="text-xl mt-2">
          Assistant Professor |AWS Cloud Certified
        </p>
       
      </header>

      {/* About Section */}
      <section className="max-w-6xl mx-auto py-16 px-6">
        <h2 className="text-3xl font-bold text-blue-900 mb-6">About Me</h2>
        <div className="bg-white rounded-2xl shadow-md p-8">
          <p className="text-lg leading-8">
            Dedicated academic professional with expertise in Database,
            Operating System, Cloud Computing,OOPM.
            Passionate about teaching, mentoring students, conducting research,
            and contributing to academic innovation.
          </p>
        </div>
      </section>

      {/* Education */}
      <section className="bg-white py-16 px-6">
        <div className="max-w-6xl mx-auto">
          <h2 className="text-3xl font-bold text-blue-900 mb-8">Education</h2>
          <div className="grid md:grid-cols-2 gap-6">
            <div className="bg-gray-50 rounded-2xl shadow p-6">
              <h3 className="text-xl font-semibold">Ph.D. Pursuing</h3>
              <p>Computer Science Engineering </p>
              <p className="text-gray-600">Oriental University Indore</p>
            </div>
            <div className="bg-gray-50 rounded-2xl shadow p-6">
              <h3 className="text-xl font-semibold">Master’s Degree</h3>
              <p>Computer Engineering</p>
              <p className="text-gray-600">DAVV University </p>
            </div>
          </div>
        </div>
      </section>

      {/* Subjects Taught */}
      <section className="max-w-6xl mx-auto py-16 px-6">
        <h2 className="text-3xl font-bold text-blue-900 mb-8">Subjects Taught</h2>
        <div className="grid md:grid-cols-3 gap-6">
          {[
            "Database Management System",
            "Operating System",
            "Cloud Computing",
            "AWS Fundamentals",
            "Object Oriented Programming",
            "Digital Marketing",
          ].map((subject, index) => (
            <div
              key={index}
              className="bg-white shadow-md rounded-2xl p-6 hover:shadow-xl transition"
            >
              <h3 className="text-lg font-semibold">{subject}</h3>
            </div>
          ))}
        </div>
      </section>

      {/* Skills */}
      <section className="bg-blue-50 py-16 px-6">
        <div className="max-w-6xl mx-auto">
          <h2 className="text-3xl font-bold text-blue-900 mb-8">Professional Skills</h2>
          <div className="grid md:grid-cols-2 gap-6">
            {[
              "Teaching & Mentoring",              
              "AWS Cloud Computing",
              "Research ",
              "Presentation & Communication",
            ].map((skill, index) => (
              <div
                key={index}
                className="bg-white rounded-xl shadow p-5"
              >
                <p className="font-medium">{skill}</p>
              </div>
            ))}
          </div>
        </div>
      </section>

      {/* Research & Publications */}
      <section className="max-w-6xl mx-auto py-16 px-6">
        <h2 className="text-3xl font-bold text-blue-900 mb-8">
          Research & Publications
        </h2>
        <div className="space-y-6">
          {[1].map((item) => (
            <div
              key={item}
              className="bg-white rounded-2xl shadow-md p-6"
            >
              <h3 className="text-xl font-semibold">
               10+ publications in reputed journals/ conferences
              </h3>
              
            </div>
          ))}
        </div>
      </section>

      {/* Certifications */}
      <section className="bg-white py-16 px-6">
        <div className="max-w-6xl mx-auto">
          <h2 className="text-3xl font-bold text-blue-900 mb-8">Certifications</h2>
          <div className="grid md:grid-cols-3 gap-6">
            {[
              "AWS Cloud Practitioner",
              "Google Cloud Data Analytics",
              "NPTEL Mentor Certificates",
            ].map((cert, index) => (
              <div
                key={index}
                className="bg-gray-50 rounded-2xl shadow p-6 text-center"
              >
                <h3 className="font-semibold text-lg">{cert}</h3>
              </div>
            ))}
          </div>
        </div>
      </section>

      {/* Achievements */}
      <section className="max-w-6xl mx-auto py-16 px-6">
        <h2 className="text-3xl font-bold text-blue-900 mb-8">Achievements</h2>
        <div className="bg-white rounded-2xl shadow-md p-8">
          <ul className="list-disc pl-6 space-y-3 text-lg">
            <li>Presented research papers at national and international conferences.</li>
            <li>Mentored student academic and technical projects.</li>
            <li>Recognized for academic excellence and innovation in teaching.</li>
          </ul>
        </div>
      </section>

      {/* Contact */}
      <section className="bg-blue-900 text-white py-16 px-6">
        <div className="max-w-4xl mx-auto text-center">
          <h2 className="text-3xl font-bold mb-6">Contact</h2>
          <p className="text-lg mb-3">📧 manojkumargupta@acropolis.in</p>
          <p className="text-lg mb-3">📞 +91 92010 49100</p>
          <p className="text-lg mb-3">🏫 Acropolis Institute of Technology and Research, Indore</p>
          <p className="text-lg">📍 Madhya Pradesh, India</p>
        </div>
      </section>

      {/* Footer */}
      <footer className="bg-gray-950 text-gray-400 text-center py-6">
        <p>© 2026 Manoj Kumar Gupta. All Rights Reserved.</p>
      </footer>
    </div>
  );
}
