import React from "react";
import { Card, CardContent } from "@/components/ui/card";
import { Button } from "@/components/ui/button";

export default function Portfolio() {
  return (
    <div className="min-h-screen bg-gray-900 text-white p-6">
      {/* Hero Section */}
      <section className="text-center py-10">
        <h1 className="text-4xl font-bold mb-2">Mahidhar</h1>
        <p className="text-lg mb-4">Building data-driven solutions and smart products</p>
        <Button className="bg-blue-500 hover:bg-blue-600">Download Resume</Button>
      </section>
      {/* About Section */}
      <section className="py-10">
        <h2 className="text-2xl font-semibold mb-4">About Me</h2>
        <p className="max-w-3xl mx-auto">
          I’m a B.Tech IT student with a deep interest in Machine Learning, Data Analytics, and Full Stack Development. I currently lead a team working on a real-time credit card fraud detection system using Python and ML tools. I’m also passionate about building practical startups that solve everyday problems.
        </p>
      </section>
      {/* Skills Section */}
      <section className="py-10">
        <h2 className="text-2xl font-semibold mb-4">Skills</h2>
        <div className="grid grid-cols-2 md:grid-cols-3 gap-4 text-center">
          <Card><CardContent>Python</CardContent></Card>
          <Card><CardContent>JavaScript</CardContent></Card>
          <Card><CardContent>SQL</CardContent></Card>
          <Card><CardContent>React</CardContent></Card>
          <Card><CardContent>TensorFlow</CardContent></Card>
          <Card><CardContent>Scikit-Learn</CardContent></Card>
        </div>
      </section>
      {/* Projects Section */}
      <section className="py-10">
        <h2 className="text-2xl font-semibold mb-4">Projects</h2>
        <div className="grid gap-6 md:grid-cols-2">
          <Card>
            <CardContent>
              <h3 className="text-xl font-bold">Real-Time Credit Card Fraud Detection</h3>
              <p>Used supervised learning and anomaly detection to identify fraud. Tech: Python, Sklearn, TensorFlow, SQL.</p>
            </CardContent>
          </Card>
          <Card>
            <CardContent>
              <h3 className="text-xl font-bold">Career Development Roadmap Website</h3>
              <p>Built with HTML, CSS, JS to guide engineering students across branches.</p>
            </CardContent>
          </Card>
          <Card>
            <CardContent>
              <h3 className="text-xl font-bold">Money Manager App</h3>
              <p>Budgeting tool made with React and local storage for expense tracking.</p>
            </CardContent>
          </Card>
        </div>
      </section> 
      {/* Contact Section */}
      <section className="py-10 text-center">
        <h2 className="text-2xl font-semibold mb-4">Contact</h2>
        <p>Connect with me on <a href="#" className="text-blue-400 underline">LinkedIn</a> or <a href="mailto:youremail@example.com" className="text-blue-400 underline">send me an email</a>.</p>
      </section>
    </div>
  );
}
