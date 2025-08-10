# Current Team Members

<style>
.member-card {
    border: 1px solid #ddd;
    border-radius: 8px;
    padding: 15px;
    margin: 10px;
    text-align: center;
    transition: all 0.3s ease;
    position: relative;
    overflow: visible;
    min-height: 280px;
}

.member-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 8px 25px rgba(0,0,0,0.15);
    border-color: var(--md-primary-fg-color);
    z-index: 10;
}

.member-photo {
    width: 120px;
    height: 120px;
    border-radius: 50%;
    object-fit: cover;
    margin: 0 auto 10px;
    display: block;
    border: 3px solid #fff;
    box-shadow: 0 2px 10px rgba(0,0,0,0.1);
}

.member-info {
    opacity: 0;
    position: absolute;
    top: -20px;
    left: -20px;
    right: -20px;
    background: rgba(63, 81, 181, 0.96);
    color: white;
    padding: 25px;
    border-radius: 12px;
    transform: translateY(20px);
    transition: all 0.3s ease;
    box-shadow: 0 15px 35px rgba(0,0,0,0.3);
    z-index: 20;
    min-height: 400px;
    max-height: 500px;
    overflow-y: auto;
    backdrop-filter: blur(10px);
}

.member-card:hover .member-info {
    opacity: 1;
    transform: translateY(0);
}

.member-info h3 {
    margin-top: 0 !important;
    color: #fff !important;
    font-size: 1.3em;
    border-bottom: 2px solid rgba(255,255,255,0.3);
    padding-bottom: 8px;
    margin-bottom: 15px !important;
}

.member-info p {
    margin: 8px 0 !important;
    line-height: 1.5;
    font-size: 0.9em;
    color: rgba(255,255,255,0.95) !important;
}

.member-info strong {
    color: #fff !important;
    font-weight: 600;
}

.member-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 30px;
    margin: 30px 0;
    padding: 20px 0;
}

/* 响应式调整 */
@media (max-width: 768px) {
    .member-info {
        position: fixed;
        top: 50%;
        left: 50%;
        right: auto;
        transform: translate(-50%, -50%) scale(0.9);
        width: 90vw;
        max-width: 400px;
        max-height: 70vh;
    }
    
    .member-card:hover .member-info {
        transform: translate(-50%, -50%) scale(1);
    }
    
    .member-grid {
        grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
        gap: 15px;
    }
}
</style>

## Postdoctoral Researchers

<div class="member-grid">

<div class="member-card">
    <img src="../../assets/Test.svg" alt="Dr. Zhang" class="member-photo">
    <h3>Dr. Zhang Wei</h3>
    <p><strong>Postdoctoral Researcher</strong></p>
    <p>Structural Dynamics</p>
    
    <div class="member-info">
        <h3>Dr. Zhang Wei</h3>
        <p><strong>Research Focus:</strong> Earthquake engineering, structural vibration control</p>
        <p><strong>Education:</strong> PhD in Civil Engineering, Tsinghua University (2022)</p>
        <p><strong>Interests:</strong> Rock climbing, photography, classical music</p>
        <p><strong>Languages:</strong> Chinese (native), English (fluent), Japanese (basic)</p>
        <p><strong>Email:</strong> zhang.wei@university.edu</p>
    </div>
</div>

<div class="member-card">
    <img src="../../assets/Test.svg" alt="Dr. Smith" class="member-photo">
    <h3>Dr. Sarah Smith</h3>
    <p><strong>Postdoctoral Researcher</strong></p>
    <p>Sustainable Materials</p>
    
    <div class="member-info">
        <h3>Dr. Sarah Smith</h3>
        <p><strong>Research Focus:</strong> Green concrete, recycled materials, life cycle assessment</p>
        <p><strong>Education:</strong> PhD in Materials Science, MIT (2023)</p>
        <p><strong>Interests:</strong> Hiking, sustainable living, cooking</p>
        <p><strong>Publications:</strong> 15 journal papers, 2 book chapters</p>
        <p><strong>Email:</strong> sarah.smith@university.edu</p>
    </div>
</div>

</div>

---

## PhD Students

<div class="member-grid">

<div class="member-card">
    <img src="../../assets/Test.svg" alt="Li Ming" class="member-photo">
    <h3>Li Ming</h3>
    <p><strong>PhD Student (3rd year)</strong></p>
    <p>Smart Infrastructure</p>
    
    <div class="member-info">
        <h3>Li Ming</h3>
        <p><strong>Research Topic:</strong> IoT sensors for bridge health monitoring</p>
        <p><strong>Expected Graduation:</strong> 2026</p>
        <p><strong>Background:</strong> MS in Civil Engineering, Beijing University</p>
        <p><strong>Interests:</strong> Gaming, badminton, AI technology</p>
        <p><strong>Current Project:</strong> Wireless sensor network optimization</p>
    </div>
</div>

<div class="member-card">
    <img src="../../assets/Test.svg" alt="Chen Xiao" class="member-photo">
    <h3>Chen Xiao</h3>
    <p><strong>PhD Student (2nd year)</strong></p>
    <p>Computational Mechanics</p>
    
    <div class="member-info">
        <h3>Chen Xiao</h3>
        <p><strong>Research Topic:</strong> Machine learning in finite element analysis</p>
        <p><strong>Expected Graduation:</strong> 2027</p>
        <p><strong>Background:</strong> MS in Mechanical Engineering, Shanghai Jiao Tong University</p>
        <p><strong>Interests:</strong> Machine learning, swimming, science fiction</p>
        <p><strong>Skills:</strong> Python, MATLAB, ANSYS</p>
    </div>
</div>

<div class="member-card">
    <img src="../../assets/Test.svg" alt="Wang Lei" class="member-photo">
    <h3>Wang Lei</h3>
    <p><strong>PhD Student (1st year)</strong></p>
    <p>Geotechnical Engineering</p>
    
    <div class="member-info">
        <h3>Wang Lei</h3>
        <p><strong>Research Topic:</strong> Soil-structure interaction in high-rise buildings</p>
        <p><strong>Expected Graduation:</strong> 2028</p>
        <p><strong>Background:</strong> BS in Civil Engineering, Tongji University</p>
        <p><strong>Interests:</strong> Basketball, traveling, drone photography</p>
        <p><strong>Goal:</strong> Become a leading expert in foundation design</p>
    </div>
</div>

</div>

---

## Master's Students

<div class="member-grid">

<div class="member-card">
    <img src="../../assets/Test.svg" alt="Liu Yan" class="member-photo">
    <h3>Liu Yan</h3>
    <p><strong>Master's Student (2nd year)</strong></p>
    <p>Structural Analysis</p>
    
    <div class="member-info">
        <h3>Liu Yan</h3>
        <p><strong>Research Topic:</strong> Seismic analysis of steel frame structures</p>
        <p><strong>Expected Graduation:</strong> 2025</p>
        <p><strong>Background:</strong> BS in Civil Engineering, Harbin Institute of Technology</p>
        <p><strong>Interests:</strong> Dancing, reading, volunteer work</p>
        <p><strong>Career Goal:</strong> Structural design engineer</p>
    </div>
</div>

<div class="member-card">
    <img src="../../assets/Test.svg" alt="Zhao Mei" class="member-photo">
    <h3>Zhao Mei</h3>
    <p><strong>Master's Student (1st year)</strong></p>
    <p>Environmental Engineering</p>
    
    <div class="member-info">
        <h3>Zhao Mei</h3>
        <p><strong>Research Topic:</strong> Water treatment in construction sites</p>
        <p><strong>Expected Graduation:</strong> 2026</p>
        <p><strong>Background:</strong> BS in Environmental Science, Fudan University</p>
        <p><strong>Interests:</strong> Environmental protection, yoga, painting</p>
        <p><strong>Aspiration:</strong> Sustainable construction consulting</p>
    </div>
</div>

<div class="member-card">
    <img src="../../assets/Test.svg" alt="Sun Hao" class="member-photo">
    <h3>Sun Hao</h3>
    <p><strong>Master's Student (1st year)</strong></p>
    <p>Construction Management</p>
    
    <div class="member-info">
        <h3>Sun Hao</h3>
        <p><strong>Research Topic:</strong> BIM implementation in construction projects</p>
        <p><strong>Expected Graduation:</strong> 2026</p>
        <p><strong>Background:</strong> BS in Civil Engineering, Southeast University</p>
        <p><strong>Interests:</strong> Project management, soccer, guitar</p>
        <p><strong>Software Skills:</strong> AutoCAD, Revit, Primavera</p>
    </div>
</div>

</div>

---

## Research Assistants

### Undergraduate Research Assistants

<div class="member-grid">

<div class="member-card">
    <img src="../../assets/Test.svg" alt="Kim Ji-won" class="member-photo">
    <h3>Kim Ji-won</h3>
    <p><strong>Research Assistant</strong></p>
    <p>Data Analysis</p>
    
    <div class="member-info">
        <h3>Kim Ji-won</h3>
        <p><strong>Year:</strong> Senior (4th year)</p>
        <p><strong>Major:</strong> Civil Engineering</p>
        <p><strong>Task:</strong> Laboratory data processing and visualization</p>
        <p><strong>Interests:</strong> Data science, tennis, K-pop</p>
        <p><strong>Future Plan:</strong> Pursuing MS degree</p>
        <p><strong>Skills:</strong> Python, R, Excel advanced functions</p>
        <p><strong>Hometown:</strong> Seoul, South Korea</p>
    </div>
</div>

<div class="member-card">
    <img src="../../assets/Test.svg" alt="Alex Jones" class="member-photo">
    <h3>Alex Jones</h3>
    <p><strong>Research Assistant</strong></p>
    <p>Lab Maintenance</p>
    
    <div class="member-info">
        <h3>Alex Jones</h3>
        <p><strong>Year:</strong> Junior (3rd year)</p>
        <p><strong>Major:</strong> Mechanical Engineering</p>
        <p><strong>Task:</strong> Equipment calibration and maintenance</p>
        <p><strong>Interests:</strong> Robotics, 3D printing, cycling</p>
        <p><strong>Skills:</strong> CAD design, Python programming</p>
        <p><strong>Future Goal:</strong> Robotics engineering</p>
        <p><strong>Favorite Project:</strong> Automated sensor calibration system</p>
    </div>
</div>

</div>

---

*Interested in joining our team? Visit our [Join us](../../join-us.md) page for current opportunities.*