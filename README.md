# Figma-design
the MobiusEngine.ai landing page from Figma Design using react
// src/App.jsx
import React from "react";

function App() {
  return (
    <div className="min-h-screen bg-gray-50 flex flex-col">
      {/* Header */}
      <header className="bg-white shadow">
        <div className="container mx-auto px-6 py-4 flex justify-between items-center">
          <h1 className="text-xl font-bold text-gray-800">MobiusEngine.ai</h1>
          <nav className="space-x-6">
            <a href="#features" className="text-gray-600 hover:text-gray-800">Features</a>
            <a href="#pricing" className="text-gray-600 hover:text-gray-800">Pricing</a>
            <a href="#contact" className="text-gray-600 hover:text-gray-800">Contact</a>
          </nav>
        </div>
      </header>

      {/* Hero Section */}
      <section className="flex-1 flex items-center justify-center text-center p-10">
        <div>
          <h2 className="text-4xl md:text-6xl font-bold text-gray-800 mb-6">Build Smarter with MobiusEngine.ai</h2>
          <p className="text-lg text-gray-600 mb-8">Next-gen AI infrastructure for developers and businesses.</p>
          <a href="#get-started" className="bg-blue-600 text-white px-6 py-3 rounded-lg shadow hover:bg-blue-700 transition">
            Get Started
          </a>
        </div>
      </section>

      {/* Features Section */}
      <section id="features" className="py-16 bg-white">
        <div className="container mx-auto px-6 text-center">
          <h3 className="text-3xl font-semibold mb-12">Powerful Features</h3>
          <div className="grid md:grid-cols-3 gap-8">
            <div className="p-6 border rounded-lg">
              <h4 className="text-xl font-bold mb-4">Scalability</h4>
              <p className="text-gray-600">Built to grow with your business effortlessly.</p>
            </div>
            <div className="p-6 border rounded-lg">
              <h4 className="text-xl font-bold mb-4">Security</h4>
              <p className="text-gray-600">Top-notch security to protect your data.</p>
            </div>
            <div className="p-6 border rounded-lg">
              <h4 className="text-xl font-bold mb-4">Customization</h4>
              <p className="text-gray-600">Tailor the platform exactly to your needs.</p>
            </div>
          </div>
        </div>
      </section>

      {/* Footer */}
      <footer className="bg-gray-800 text-white py-6 text-center">
        <p>© {new Date().getFullYear()} MobiusEngine.ai. All rights reserved.</p>
      </footer>
    </div>
  );
}

export default App;
