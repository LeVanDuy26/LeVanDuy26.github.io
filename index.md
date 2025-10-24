---
layout: default
title: "Portfolio - Lê Văn Duy"
---

<style>
.hero-section {
    text-align: center;
    padding: 2rem 0;
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    color: white;
    margin: -1rem -1rem 2rem -1rem;
}

.hero-content {
    max-width: 800px;
    margin: 0 auto;
    padding: 0 1rem;
}

.section {
    margin: 3rem 0;
    padding: 2rem;
    border-radius: 10px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    background: #f8f9fa;
}

.section h2 {
    color: #333;
    border-bottom: 3px solid #667eea;
    padding-bottom: 0.5rem;
    margin-bottom: 1.5rem;
}

.skill-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 1rem;
    margin: 1rem 0;
}

.skill-item {
    background: white;
    padding: 1rem;
    border-radius: 8px;
    border-left: 4px solid #667eea;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.project-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem;
    margin: 2rem 0;
}

.project-card {
    background: white;
    padding: 1.5rem;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease;
}

.project-card:hover {
    transform: translateY(-5px);
}

.contact-links {
    display: flex;
    justify-content: center;
    gap: 2rem;
    margin: 2rem 0;
    flex-wrap: wrap;
}

.contact-link {
    display: inline-flex;
    align-items: center;
    gap: 0.5rem;
    padding: 0.75rem 1.5rem;
    background: #667eea;
    color: white;
    text-decoration: none;
    border-radius: 25px;
    transition: background 0.3s ease;
}

.contact-link:hover {
    background: #5a6fd8;
    color: white;
}

@media (max-width: 768px) {
    .contact-links {
        flex-direction: column;
        align-items: center;
    }
    
    .skill-grid {
        grid-template-columns: 1fr;
    }
    
    .project-grid {
        grid-template-columns: 1fr;
    }
}
</style>

<div class="hero-section">
    <div class="hero-content">
        <h1>👋 Xin chào, tôi là <strong>Lê Văn Duy</strong></h1>
        <p style="font-size: 1.2rem; margin: 1rem 0;">🎓 Sinh viên Fintech tại PTIT (Học viện Công nghệ Bưu chính Viễn thông)</p>
        <p style="font-size: 1.1rem; margin: 1rem 0;">💻 Định hướng: Data Analyst trong lĩnh vực <strong>ngân hàng & tài chính</strong></p>
        <blockquote style="font-style: italic; margin: 1.5rem 0;">
            Tôi đam mê <strong>phân tích dữ liệu</strong> để khám phá insight, tối ưu hóa quy trình và hỗ trợ ra quyết định.
        </blockquote>
    </div>
</div>

<div class="section">
    <h2>📖 About Me</h2>
    <p>Xin chào, tôi là <strong>Lê Văn Duy</strong>, hiện đang là sinh viên ngành <strong>Công nghệ Tài chính (Fintech)</strong> tại PTIT. Tôi định hướng sự nghiệp trở thành <strong>Data Analyst</strong> trong ngành ngân hàng.</p>
    
    <h3>🎯 Mục tiêu nghề nghiệp</h3>
    <ul>
        <li>Trở thành <strong>Data Analyst</strong> tại ngân hàng trong 1–2 năm tới.</li>
        <li>Nâng cao kỹ năng <strong>Data Engineering</strong> để xử lý dữ liệu lớn.</li>
        <li>Xây dựng nền tảng kiến thức vững chắc về <strong>AI trong tài chính</strong>.</li>
    </ul>
</div>

<div class="section">
    <h2>🛠 Kỹ năng chính</h2>
    <div class="skill-grid">
        <div class="skill-item">
            <h4>📊 Excel nâng cao</h4>
            <p>Pivot Tables, Dashboard, Advanced Formulas</p>
        </div>
        <div class="skill-item">
            <h4>🗄️ SQL (MySQL)</h4>
            <p>Query, Join, Group By, Window Functions</p>
        </div>
        <div class="skill-item">
            <h4>🐍 Python</h4>
            <p>pandas, numpy, matplotlib, scikit-learn</p>
        </div>
        <div class="skill-item">
            <h4>📈 Power BI</h4>
            <p>DAX, Dashboard, Data Modeling</p>
        </div>
        <div class="skill-item">
            <h4>🔧 Công cụ khác</h4>
            <p>GitHub, VS Code, MySQL Workbench, DBeaver</p>
        </div>
    </div>
</div>

<div class="section">
    <h2>📂 Projects</h2>
    <div class="project-grid">
        <div class="project-card">
            <h3>🛒 Shopee Data Analysis</h3>
            <p><strong>Mục tiêu:</strong> Phân tích dữ liệu bán hàng từ Shopee để theo dõi giá, doanh thu, review</p>
            <p><strong>Công cụ:</strong> Python (pandas, matplotlib), SQL</p>
            <p><strong>Kết quả:</strong> Dashboard thể hiện top sản phẩm bán chạy, xu hướng giá</p>
            <a href="https://github.com/LeVanDuy26/shopee-analysis" target="_blank" class="contact-link">👀 Xem project</a>
        </div>
        
        <div class="project-card">
            <h3>👥 Customer Segmentation (PCA + KMeans)</h3>
            <p><strong>Mục tiêu:</strong> Phân khúc khách hàng ngân hàng dựa trên dữ liệu giao dịch</p>
            <p><strong>Công cụ:</strong> Python (pandas, scikit-learn), PCA, KMeans</p>
            <p><strong>Kết quả:</strong> Nhận diện 3 nhóm khách hàng chính, hỗ trợ chiến lược marketing</p>
            <a href="https://github.com/LeVanDuy26/customer-segmentation" target="_blank" class="contact-link">👀 Xem project</a>
        </div>
        
        <div class="project-card">
            <h3>📊 Power BI Business Dashboard</h3>
            <p><strong>Mục tiêu:</strong> Trực quan hóa dữ liệu kinh doanh giúp lãnh đạo đưa ra quyết định nhanh</p>
            <p><strong>Công cụ:</strong> Power BI, Excel</p>
            <p><strong>Kết quả:</strong> Dashboard theo dõi doanh thu, sản phẩm, khách hàng</p>
            <a href="#" class="contact-link">👀 Xem dashboard</a>
        </div>
    </div>
</div>

<div class="section">
    <h2>📄 Resume</h2>
    <p>Bạn có thể tải CV của tôi tại đây:</p>
    <div style="text-align: center; margin: 2rem 0;">
        <a href="/assets/cv/LeVanDuy_CV.pdf" class="contact-link" download>📥 Download CV (PDF)</a>
    </div>
    
    <h3>📋 Tóm tắt</h3>
    <ul>
        <li>🎓 Sinh viên Fintech tại PTIT</li>
        <li>💻 Định hướng Data Analyst (Banking/Finance)</li>
        <li>📊 Kỹ năng: Excel, SQL, Python, Power BI</li>
        <li>📂 Dự án: Shopee Data Analysis, Customer Segmentation, Power BI Dashboard</li>
    </ul>
</div>

<div class="section">
    <h2>📩 Contact</h2>
    <p style="text-align: center; margin: 2rem 0;">Nếu bạn muốn trao đổi thêm, hãy liên hệ qua:</p>
    <div class="contact-links">
        <a href="mailto:levanduy26052004@gmail.com" class="contact-link">📧 Email</a>
        <a href="#" class="contact-link">💼 LinkedIn</a>
        <a href="https://github.com/LeVanDuy26" target="_blank" class="contact-link">💻 GitHub</a>
    </div>
</div>  
