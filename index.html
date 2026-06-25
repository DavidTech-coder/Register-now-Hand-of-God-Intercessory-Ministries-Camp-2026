<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Children's Camp 2026 Registration</title>
    <style>
        :root { --blue: #0a1f44; --gold: #ffd700; }
        * { box-sizing: border-box; }
        body { 
            font-family: 'Segoe UI', Arial, sans-serif; 
            background: linear-gradient(135deg, var(--blue) 0%, #1a3a6e 100%); 
            color: #fff; margin: 0; padding: 20px; min-height: 100vh; 
            display: flex; align-items: center; justify-content: center; 
        }
        .container { 
            max-width: 600px; width: 100%; background: rgba(255,255,255,0.06); 
            backdrop-filter: blur(10px); padding: 35px; border-radius: 20px; 
            border: 1px solid rgba(255,215,0,0.3); box-shadow: 0 15px 35px rgba(0,0,0,0.5);
        }
        h1 { text-align: center; color: var(--gold); font-size: 28px; margin: 0 0 5px; text-transform: uppercase; }
        .theme { text-align: center; color: #fff; margin-bottom: 8px; font-size: 15px; font-weight: 600; letter-spacing: 1px; }
        .event-info { text-align: center; font-size: 13px; margin-bottom: 25px; opacity: 0.9; color: #ddd; }
        
        label { display: block; margin-top: 15px; font-weight: 600; font-size: 14px; color: var(--gold); }
        input, select, textarea { 
            width: 100%; padding: 12px; margin-top: 5px; border-radius: 8px; 
            border: 1px solid rgba(255,215,0,0.4); background: rgba(0,0,0,0.3); 
            color: #fff; font-size: 15px; transition: 0.3s;
        }
        input:focus, select:focus, textarea:focus { outline: none; border-color: #fff; background: rgba(0,0,0,0.5); }
        
        button { 
            width: 100%; padding: 15px; margin-top: 25px; 
            background: linear-gradient(90deg, var(--gold), #ffaa00); 
            border: none; border-radius: 8px; color: var(--blue); 
            font-weight: bold; font-size: 16px; cursor: pointer; transition: 0.3s; 
        }
        button:hover { transform: translateY(-2px); box-shadow: 0 5px 15px rgba(255,215,0,0.3); }
        button:disabled { opacity: 0.6; cursor: not-allowed; transform: none; }
        
        .success { display: none; text-align: center; padding: 25px; background: rgba(0,255,0,0.1); border-radius: 10px; border: 1px solid #4caf50; }
        .success h3 { color: var(--gold); margin-top: 0; }
        .admin-link { text-align: center; margin-top: 20px; font-size: 12px; }
        .admin-link a { color: rgba(255,255,255,0.4); text-decoration: none; }
        
        .hidden { display: none; }
    </style>
</head>
<body>

<div class="container">
    <div id="formContainer">
        <h1>CHILDREN'S CAMP 2026</h1>
        <p class="theme">Theme: CHILDREN ARE ARROWS - Psalm 127:4+</p>
        <p class="event-info">27th-29th August 2026 | Dominion Camp, Ganmo, Ilorin</p>

        <form id="regForm">
            <input type="text" name="_honey" class="hidden">
            <input type="hidden" id="timeUsed" name="timeUsed">

            <label>Child's Full Name *</label>
            <input type="text" name="childName" required placeholder="Surname First">

            <label>Age *</label>
            <input type="number" name="age" min="4" max="17" required>

            <label>Gender *</label>
            <select name="gender" required>
                <option value="">Select Gender</option>
                <option value="Male">Male</option>
                <option value="Female">Female</option>
            </select>

            <label>Parent/Guardian Full Name *</label>
            <input type="text" name="parentName" required>

            <label>Phone Number *</label>
            <input type="tel" name="phone" required placeholder="080xxxxxxxx">

            <label>Email Address</label>
            <input type="email" name="email" placeholder="optional@mail.com">

            <label>Home Address</label>
            <textarea name="address" rows="2" placeholder="Residential address"></textarea>

            <label>Medical/Allergy Information</label>
            <textarea name="medical" rows="2" placeholder="Any allergies, asthma, medication, etc"></textarea>

            <button type="submit" id="submitBtn">REGISTER CHILD</button>
        </form>
    </div>

    <div class="success" id="successMsg">
        <h3>Registration Successful!</h3>
        <p>Thank you for registering. We have received your details. God bless you!</p>
        <button onclick="window.location.reload()">Register Another Child</button>
    </div>

    <div class="admin-link">
        <a href="#">© 2026 Children's Camp Admin</a>
    </div>
</div>

<script>
    const API_URL = 'https://script.google.com/macros/s/AKfycbzGz47Tg03bGYTSDEAa1PQ3ae0G2QasnqwPfs-S7oZwHtlAKGZXQlSq7ySd50ld5Pz9oA/exec';
    
    // 1. Start timer as soon as page loads
    const startTime = Date.now();

    document.getElementById('regForm').addEventListener('submit', function(e) {
        e.preventDefault();
        
        const btn = document.getElementById('submitBtn');
        const form = this;
        
        if(form._honey.value) return;

        btn.disabled = true;
        btn.textContent = 'Processing...';

        // 2. Calculate seconds spent
        const endTime = Date.now();
        const secondsSpent = Math.floor((endTime - startTime) / 1000);
        document.getElementById('timeUsed').value = secondsSpent;

        const formData = new FormData(form);
        const data = {};
        
        formData.forEach((value, key) => {
            if(key !== '_honey') data[key] = value;
        });

        // Adding metadata for your dashboard
        data.submissionTime = new Date().toLocaleString();
        data.duration = secondsSpent; // Sent as a number for easier math in the sheet

        fetch(API_URL, {
            method: 'POST',
            mode: 'no-cors', 
            cache: 'no-cache',
            headers: { 'Content-Type': 'application/json' },
            body: JSON.stringify(data)
        })
        .then(() => {
            document.getElementById('formContainer').style.display = 'none';
            document.getElementById('successMsg').style.display = 'block';
        })
        .catch(err => {
            console.error(err);
            alert('There was an error. Please check your connection.');
            btn.disabled = false;
            btn.textContent = 'REGISTER CHILD';
        });
    });
</script>

</body>
</html>
