  <h1>Humanly AI 🤖✍️</h1> 
  <a href="https://humanlybot2026.lovable.app/" target="_blank" rel="noopener noreferrer">
  <button style="
    background-color:#2f8f7a;
    color:white;
    padding:10px 18px;
    border:none;
    border-radius:8px;
    cursor:pointer;
    font-size:16px;
  ">
    Humanly AI
  </button>
</a>


  <p>
    <strong>Humanly AI</strong> is an AI-powered content generation platform that creates
    <strong>humanized content</strong> for <strong>LinkedIn posts, blogs, and emails</strong>.
    The project is built using <strong>Lovable (frontend)</strong> and <strong>n8n (automation backend)</strong>,
    leveraging AI agents, webhooks, and workflow orchestration.
  </p>

  <div class="section">
    <h2>🚀 Project Overview</h2>
    <p>
      Humanly AI allows users to generate high-quality, natural-sounding content by providing
      a few simple inputs. Once the user submits the required details, an automated workflow
      is triggered through webhooks, processed by AI agents in n8n, and the generated content
      is returned and displayed on the frontend.
    </p>
  </div>

  <div class="section">
    <h2>🧠 Key Features</h2>
    <ul>
      <li>Humanized AI-generated content</li>
      <li>Supports LinkedIn, Blog, and Email content</li>
      <li>Simple and intuitive frontend UI</li>
      <li>Fully automated backend using n8n</li>
      <li>Real-time webhook-based processing</li>
      <li>Markdown and HTML formatted outputs</li>
    </ul>
  </div>

  <div class="section">
    <h2>🧩 Required User Inputs</h2>
    <p>The following four inputs are mandatory:</p>
    <ul>
      <li><strong>Target Audience</strong></li>
      <li><strong>Number of Words</strong></li>
      <li><strong>Content Type</strong> (LinkedIn / Blog / Email)</li>
      <li><strong>Basic Content Description</strong></li>
    </ul>
  </div>

  <div class="section">
    <h2>🏗️ Architecture Overview</h2>
    <pre>
User (Lovable Frontend)
        ↓
Form Submission
        ↓
Webhook Trigger (n8n)
        ↓
AI Agent Processing
        ↓
Content Generation
        ↓
Webhook Response
        ↓
Frontend Display (Humanly AI)
    </pre>
  </div>

  <div class="section">
    <h2>🛠️ Tech Stack</h2>
    <h3>Frontend</h3>
    <ul>
      <li>Lovable</li>
      <li>Custom UI for content input and output display</li>
    </ul>

  <h3>Backend / Automation</h3>
<ul>
  <li>n8n (workflow automation)</li>
  <li>Webhook-based triggers and responses</li>
  <li>AI-driven automation using agents</li>
</ul>

  </div>

  <div class="section">
    <h2>🔧 n8n Nodes Used</h2>
    <ul>
      <li><strong>Webhook Node</strong> – Triggers workflow from frontend</li>
      <li><strong>Set Node</strong> – Structures and prepares input data</li>
      <li><strong>AI Agent Node</strong> – Generates humanized content</li>
      <li><strong>Code Node</strong> – Custom logic and data processing</li>
      <li><strong>Markdown Node</strong> – Formats AI-generated content</li>
      <li><strong>HTML Node</strong> – Prepares content for frontend rendering</li>
    </ul>
  </div>

  <div class="section">
    <h2>⚙️ Workflow Explanation</h2>
    <ol>
      <li>User submits content requirements on the frontend</li>
      <li>Frontend sends data to n8n via webhook</li>
      <li>Webhook triggers the automation workflow</li>
      <li>AI agent processes inputs and generates content</li>
      <li>Content is formatted using Markdown and HTML nodes</li>
      <li>Final output is returned to the frontend</li>
      <li>Generated content is displayed to the user</li>
    </ol>
  </div>

  <div class="section">
    <h2>📌 Use Cases</h2>
    <ul>
      <li>LinkedIn post generation</li>
      <li>Blog content creation</li>
      <li>Professional email drafting</li>
      <li>Marketing and personal branding content</li>
    </ul>
  </div>

  <div class="section">
    <h2>📈 Scope & Future Enhancements</h2>
    <ul>
      <li>User authentication</li>
      <li>Content history and versioning</li>
      <li>Multi-language support</li>
      <li>Tone selection (formal, casual, persuasive)</li>
      <li>SEO optimization for blog content</li>
      <li>Public API for integrations</li>
    </ul>
  </div>

  <div class="section">
    <h2>👨‍💻 Author</h2>
    <p>
      <strong>Sajid Shaik</strong><br/>
      Automation & AI Enthusiast<br/>
      Built with ❤️ using Lovable and n8n
    </p>
  </div>

  <div class="section">
    <h2>📄 License</h2>
    <p>
      This project is created for learning and demonstration purposes.
      You are free to fork, modify, and enhance it.
    </p>
  </div>

</body>
</html>
