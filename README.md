## Hi there 👋

<!--
**ahmedabdin22/ahmedabdin22** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...<!doctype html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title> مراجعات الثانوية العامة</title>
  <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;700&amp;family=Aref+Ruqaa&amp;family=Scheherazade+New:wght@400;700&amp;family=Amiri:wght@400;700&amp;display=swap" rel="stylesheet">
  <style>
    /* Updated Dark Palette with a touch of blue/green */
    :root {
      --bg-color: #0F1D2F; /* Deeper, richer Navy Blue for a premium feel */
      --text-color: #E6E6E6; /* Lighter gray for better contrast */
      --primary-color: #BB86FC; /* Soft Purple */
      --secondary-color: #03DAC6; /* Teal */
      --card-bg: #1A2E40; /* Darker blue-gray for cards */
      --border-color: #3C5A79; /* Muted blue border */
      --hover-bg: #2B4560; /* For hover states */
      --header-bg-start: #1A2E40; /* Start of header gradient (matches card_bg) */
      --header-bg-end: #0F1D2F; /* End of header gradient (matches bg_color) */
      --sallu-color: #000000; /* Black for "Sallu ala Mohamed" */
      --folder-bg: #21374F; /* Slightly lighter blue-gray for folders */
      --folder-border: #4A6C8C; /* Folder border */
      --footer-text-color: #888888;
      --dropdown-bg: #1A2E40;
      --dropdown-border: #3C5A79;
      --dropdown-hover-bg: #2B4560;

      /* New: Quran Verse Colors */
      --quran-text-color: #FFD700; /* Gold color for Quran verse */
      --quran-shadow-color-1: rgba(255, 215, 0, 0.8); /* Stronger gold shadow */
      --quran-shadow-color-2: rgba(255, 215, 0, 0.6); /* Even stronger gold shadow */
      --quran-light-text-color: #4A4A4A; /* Darker grey for light mode Quran */
      --quran-light-shadow-1: rgba(0, 0, 0, 0.25);
      --quran-light-shadow-2: rgba(0, 0, 0, 0.15);

      /* New: By.ENG Ahmed Abdin color */
      --signature-color: #E6E6E6; /* Same as main text color */
      --signature-light-color: #333333; /* Same as main text color in light mode */
    }

    /* Light Mode Colors */
    body.light-mode {
      --bg-color: #F8FBFD; /* Very light blue-gray for soft look */
      --text-color: #333333;
      --primary-color: #6200EE;
      --secondary-color: #03DAC6;
      --card-bg: #FFFFFF;
      --border-color: #E0E0E0;
      --hover-bg: #E6EEF4;
      --header-bg-start: #F8FBFD;
      --header-bg-end: #D9E2EC;
      --sallu-color: #333333; /* Darker for light mode */
      --folder-bg: #EAF0F6;
      --folder-border: #D1D9E0;
      --footer-text-color: #777777;
      --dropdown-bg: #FFFFFF;
      --dropdown-border: #E0E0E0;
      --dropdown-hover-bg: #F0F0F0;
      --title-color: #333333; /* Dark gray for light mode */
    }

    body {
      font-family: 'Cairo', sans-serif;
      background-color: var(--bg-color);
      color: var(--text-color);
      margin: 0;
      padding: 0;
      line-height: 1.6;
      direction: rtl;
      transition: background-color 0.4s ease, color 0.4s ease;
      /* Background pattern - Realistic subtle pattern */
      background-image: url('data:image/svg+xml,%3Csvg width="60" height="60" viewBox="0 0 60 60" xmlns="http://www.w3.org/2000/svg"%3E%3Cg fill="none" fill-rule="evenodd"%3E%3Cg fill="%23FFFFFF" fill-opacity="0.04"%3E%3Cpath d="M36 34L30 39.5l-6 5.5V59h12V34zm0 28l6 5.5v21.5H36V62zM36 0l6 5.5v21.5H36V0zM60 0l-6 5.5V27h6V0zM24 0v5.5L18 0l-6 5.5V0H0v12h12V0h12zm0 48L18 42.5l-6 5.5v12h12V48zm0-24L18 18.5l-6 5.5v12h12V24zM0 36l6 5.5v21.5H0V36zm0-24l6 5.5v21.5H0V12zm24 0l6 5.5V27h6V12h-6V0h-6v12z"/%3E%3C/g%3E%3C/g%3E%3C/svg%3E');
      background-size: 180px; /* Adjust pattern size for realism */
      background-repeat: repeat;
      background-attachment: fixed; /* Makes the pattern stationary */
    }

    body.light-mode {
        background-image: url('data:image/svg+xml,%3Csvg width="60" height="60" viewBox="0 0 60 60" xmlns="http://www.w3.org/2000/svg"%3E%3Cg fill="none" fill-rule="evenodd"%3E%3Cg fill="%23000000" fill-opacity="0.01"%3E%3Cpath d="M36 34L30 39.5l-6 5.5V59h12V34zm0 28l6 5.5v21.5H36V62zM36 0l6 5.5v21.5H36V0zM60 0l-6 5.5V27h6V0zM24 0v5.5L18 0l-6 5.5V0H0v12h12V0h12zm0 48L18 42.5l-6 5.5v12h12V48zm0-24L18 18.5l-6 5.5v12h12V24zM0 36l6 5.5v21.5H0V36zm0-24l6 5.5v21.5H0V12zm24 0l6 5.5V27h6V12h-6V0h-6v12z"/%3E%3C/g%3E%3C/g%3E%3C/svg%3E');
    }

    .container {
      max-width: 1000px;
      margin: 40px auto;
      padding: 0 25px;
    }

    /* --- Header Section --- */
    header {
      text-align: center;
      margin-bottom: 50px;
      padding: 25px;
      padding-top: 60px; /* Increased top padding to make space for positioned elements */
      background: linear-gradient(45deg, var(--header-bg-start), var(--header-bg-end));
      color: var(--text-color);
      border-radius: 12px;
      box-shadow: 0 10px 25px rgba(0, 0, 0, 0.4);
      position: relative;
      overflow: hidden;
      transition: background 0.4s ease, box-shadow 0.4s ease, color 0.4s ease;
    }

    header h1 {
      margin: 0;
      font-size: 2.8em; /* Slightly reduced font size */
      letter-spacing: 2px;
      text-shadow: 2px 2px 8px rgba(0,0,0,0.3);
      font-family: 'Scheherazade New', serif; /* New decorative font for title */
      font-weight: 700; /* Bold */
      color: var(--title-color); /* Now using --title-color for black */
      transition: color 0.4s ease;
    }

    .dark-mode-toggle {
      position: absolute;
      top: 20px; /* Adjusted top position */
      left: 20px;
      background-color: rgba(255, 255, 255, 0.15);
      color: white;
      border: none;
      padding: 10px 16px;
      border-radius: 8px;
      cursor: pointer;
      font-size: 1em;
      font-weight: bold;
      transition: background-color 0.3s ease, transform 0.2s ease;
    }

    .dark-mode-toggle:hover {
      background-color: rgba(255, 255, 255, 0.25);
      transform: translateY(-2px);
    }

    /* --- "Sallu ala Mohamed" styling --- */
    .sallu-message {
      position: absolute;
      top: 20px; /* Adjusted top position */
      right: 20px;
      font-family: 'Aref Ruqaa', serif;
      font-size: 1.2em;
      color: var(--sallu-color); /* Now black */
      text-shadow: none; /* Removed glow as per request for black color */
      font-weight: bold;
      z-index: 10;
      transition: color 0.4s ease;
    }
    body.light-mode .sallu-message {
        text-shadow: none; /* Ensure no glow in light mode either for black text */
    }


    /* --- Subject Section --- */
    .subject-section {
      background-color: var(--card-bg);
      border-radius: 12px;
      padding: 35px;
      margin-bottom: 45px;
      box-shadow: 0 6px 20px rgba(0, 0, 0, 0.35);
      border: 1px solid var(--border-color);
      transition: background-color 0.4s ease, border-color 0.4s ease, box-shadow 0.4s ease;
    }

    .subject-section h2 {
      color: var(--primary-color);
      font-size: 2.5em;
      margin-top: 0;
      margin-bottom: 30px;
      text-align: center;
      position: relative;
      transition: color 0.4s ease;
    }

    .subject-section h2::after {
      content: '';
      display: block;
      width: 100px;
      height: 4px;
      background-color: var(--secondary-color);
      margin: 18px auto 0;
      border-radius: 2px;
      transition: background-color 0.4s ease;
    }

    /* --- Teacher Card --- */
    .teacher-card {
      background-color: var(--bg-color); /* Teacher card uses main bg color */
      border-radius: 10px;
      padding: 30px;
      margin-bottom: 35px;
      border: 1px solid var(--border-color);
      box-shadow: 0 4px 15px rgba(0, 0, 0, 0.25);
      transition: transform 0.3s ease, box-shadow 0.3s ease, background-color 0.4s ease, border-color 0.4s ease;
    }

    .teacher-card:hover {
      transform: translateY(-8px);
      box-shadow: 0 12px 25px rgba(0, 0, 0, 0.5);
    }

    .teacher-card h3 {
      color: var(--secondary-color);
      font-size: 2em;
      margin-top: 0;
      margin-bottom: 25px;
      text-align: center;
      padding-bottom: 12px;
      border-bottom: 2px dashed var(--border-color);
      transition: color 0.4s ease, border-color 0.4s ease;
    }

    /* --- Folder Section (New Chic Design) --- */
    .folder-section {
      margin-bottom: 25px;
      padding: 20px;
      background-color: var(--folder-bg);
      border-radius: 10px;
      border: 1px solid var(--folder-border);
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
      transition: background-color 0.4s ease, border-color 0.4s ease, box-shadow 0.3s ease;
      position: relative;
      overflow: hidden;
    }

    .folder-section::before {
      content: '';
      position: absolute;
      top: 0;
      right: 0;
      width: 40px;
      height: 100%;
      background: linear-gradient(90deg, transparent, rgba(255, 255, 255, 0.03));
      pointer-events: none;
      transition: background 0.3s ease;
    }

    .folder-section:hover::before {
        background: linear-gradient(90deg, transparent, rgba(255, 255, 255, 0.06));
    }

    .folder-section h4 {
      color: var(--primary-color);
      font-size: 1.5em;
      margin-top: 0;
      margin-bottom: 18px;
      position: relative;
      padding-right: 35px;
      transition: color 0.4s ease;
      display: flex;
      align-items: center;
    }

    .folder-section h4::before {
      content: '📂';
      margin-left: 10px;
      font-size: 1.3em;
      color: var(--secondary-color);
      transition: color 0.4s ease;
    }

    /* --- Video Links --- */
    .video-link {
      display: flex;
      align-items: center;
      background-color: var(--card-bg);
      color: var(--text-color);
      padding: 14px 20px;
      margin-bottom: 12px;
      border-radius: 6px;
      text-decoration: none;
      transition: background-color 0.2s ease, transform 0.2s ease, color 0.2s ease, border-color 0.4s ease;
      border: 1px solid var(--border-color);
      box-shadow: 0 2px 8px rgba(0, 0, 0, 0.15);
    }

    .video-link:hover {
      background-color: var(--secondary-color);
      color: white;
      transform: translateX(-8px);
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.3);
    }

    .video-link::before {
      content: '▶️'; /* Default video icon */
      margin-left: 12px;
      font-size: 1.3em;
      color: var(--primary-color);
      transition: color 0.2s ease;
    }
    
    /* Specific styling for the 'exams-link' to change its icon */
    .exams-link.video-link::before { /* Added .video-link to increase specificity */
        content: '📁'; /* Folder icon for exams link */
        color: var(--secondary-color); /* Use secondary color for distinction */
    }

    .video-link:hover::before {
      color: white;
    }

    /* --- Dropdown for Subject Selection --- */
    .subject-selector {
        text-align: left; /* Aligned to the left */
        margin-bottom: 40px;
        padding-left: 20px; /* Add some padding from the left edge */
    }

    .subject-selector label {
        font-size: 1.4em;
        color: var(--primary-color);
        margin-right: 15px; /* Adjusted margin for left alignment */
        font-weight: bold;
    }

    .subject-selector select {
        padding: 12px 20px;
        border-radius: 8px;
        border: 2px solid var(--dropdown-border);
        background-color: var(--dropdown-bg);
        color: var(--text-color);
        font-size: 1.2em;
        cursor: pointer;
        outline: none;
        appearance: none;
        background-image: url('data:image/svg+xml;charset=US-ASCII,%3Csvg%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%20width%3D%22292.4%22%20height%3D%22292.4%22%3E%3Cpath%20fill%3D%22%23e0e0e0%22%20d%3D%22M287%2C197.3L159.1%2C69.5c-3.6-3.6-8.4-5.6-13.6-5.6s-10%2C2-13.6%2C5.6L5.4%2C197.3c-7.2%2C7.2-7.2%2C18.8%2C0%2C26c7.2%2C7.2%2C18.8%2C7.2%2C26%2C0l114.7-114.7L261%2C223.3c7.2%2C7.2%2C18.8%2C7.2%2C26%2C0C294.2%2C216.1%2C294.2%2C204.5%2C287%2C197.3z%22%2F%3E%3C%2Fsvg%3E');
        background-repeat: no-repeat;
        background-position: right 15px center; /* Position arrow to the right for RTL */
        background-size: 1em;
        padding-right: 40px; /* Space for the arrow */
        padding-left: 20px; /* Restore left padding for text */
        box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        transition: border-color 0.3s ease, background-color 0.3s ease, color 0.3s ease;
    }

    .subject-selector select:hover {
        border-color: var(--secondary-color);
    }

    .subject-selector select option {
        background-color: var(--dropdown-bg);
        color: var(--text-color);
    }

    /* Hide all subject sections by default */
    .subject-section {
        display: none;
    }

    /* Display active subject section */
    .subject-section.active {
        display: block;
    }

    /* --- Quranic Verse --- */
    .quran-verse {
        text-align: center;
        font-family: 'Aref Ruqaa', serif;
        font-size: 2em; /* Increased font size */
        color: var(--quran-text-color); /* Changed to gold color */
        margin-top: 50px;
        margin-bottom: 10px; /* Reduced margin to bring signature closer */
        line-height: 2.2; /* Increased line height for better spacing */
        text-shadow: 0 0 12px var(--quran-shadow-color-1), /* Stronger glow */
                     0 0 20px var(--quran-shadow-color-2); /* Even stronger glow */
        font-weight: bold; /* Ensure bold */
        transition: color 0.4s ease, text-shadow 0.4s ease; /* Smooth transition */
    }
    .quran-verse .verse-info {
        display: block; /* Make sure verse info is on a new line */
        font-size: 0.6em; /* Smaller font for verse info */
        color: var(--text-color); /* Normal text color for info */
        margin-top: 10px;
        transition: color 0.4s ease;
    }
    body.light-mode .quran-verse {
        color: var(--quran-light-text-color); /* Darker text for light mode */
        text-shadow: 0 0 10px var(--quran-light-shadow-1), /* Subtle shadow for black text in light mode */
                     0 0 15px var(--quran-light-shadow-2);
    }


    /* --- Signature Section --- */
    .signature-section {
        text-align: center;
        margin-bottom: 60px; /* Increased margin for better separation */
        font-family: 'Cairo', sans-serif;
        font-size: 1.1em;
        line-height: 1.5;
        color: var(--text-color); /* Default text color */
        transition: color 0.4s ease;
    }
    .signature-section p {
        margin: 0;
    }
    .signature-section .name-signature {
        font-size: 1.2em; /* Slightly larger for the name */
        font-weight: 700; /* Bold */
        color: inherit; /* Inherit color from parent (.signature-section) */
        transition: color 0.4s ease;
        font-family: 'Amiri', serif; /* A more decorative font for the signature */
        letter-spacing: 0.5px; /* Slight letter spacing for elegance */
        text-shadow: 0 0 5px rgba(255,255,255,0.1); /* Subtle glow effect for "مزغرفة" feel */
    }
    body.light-mode .signature-section .name-signature {
        color: inherit; /* Also inherit in light mode */
        text-shadow: 0 0 3px rgba(0,0,0,0.1);
    }

    /* --- Success Message (Now "بالتوفيق") --- */
    .success-message {
      text-align: center;
      font-family: 'Cairo', sans-serif;
      font-size: 2.2em;
      color: var(--secondary-color);
      margin-top: 20px;
      margin-bottom: 60px;
      font-weight: bold;
      text-shadow: 0 0 10px var(--secondary-color), 0 0 20px rgba(0, 188, 212, 0.5);
      transition: color 0.4s ease, text-shadow 0.4s ease;
    }

    /* --- Footer --- */
    footer {
      margin-top: 50px;
      text-align: center;
      color: var(--footer-text-color);
      font-size: 1em;
      padding-bottom: 25px;
      border-top: 1px solid var(--border-color);
      padding-top: 25px;
      transition: color 0.4s ease, border-color 0.4s ease;
      position: relative; /* Needed for absolute positioning of social section */
      min-height: 100px; /* Give it some minimum height to contain the positioned element */
    }

    footer p {
      margin-bottom: 8px;
    }

    /* Styling for the social section in the footer */
    .footer-social-section {
        position: absolute; /* Position absolutely within the footer */
        bottom: 25px; /* Aligned to the bottom padding */
        right: 25px; /* Aligned to the right padding */
        display: flex; /* Use flexbox for alignment */
        align-items: center; /* Vertically align icon and text */
        gap: 15px; /* Space between social links */
    }

    .footer-social-link {
        display: inline-flex; /* Use inline-flex for alignment with text */
        align-items: center; /* Vertically align icon and text */
        text-decoration: none;
        color: inherit; /* Inherit text color from footer */
        transition: transform 0.2s ease;
    }

    .footer-social-link:hover {
        transform: translateY(-3px); /* Lift effect on hover */
    }

    .footer-social-link span {
        margin-left: 10px; /* Space between text and icon for RTL */
        font-size: 1.1em; /* Make text slightly larger */
        font-weight: bold;
        color: var(--text-color); /* Ensure text is visible in both modes */
        transition: color 0.4s ease;
    }

    .social-icon-svg {
        width: 32px; /* Increased size for prominence */
        height: 32px;
        background-color: #000000; /* Black background for the square */
        fill: #FFFFFF; /* White logo */
        border-radius: 6px; /* Slightly more rounded corners for app icon feel */
        box-shadow: 0 3px 8px rgba(0, 0, 0, 0.3); /* Clearer shadow */
        transition: box-shadow 0.2s ease, background-color 0.2s ease;
    }
    .footer-social-link:hover .social-icon-svg {
        box-shadow: 0 5px 15px rgba(0, 0, 0, 0.4); /* Stronger shadow on hover */
    }

    /* Specific Facebook icon styling */
    .facebook-icon-svg {
        background-color: #1877F2; /* Facebook Blue */
    }

    /* Specific Instagram icon styling */
    .instagram-icon-svg {
        background: radial-gradient(circle at 30% 107%, #fdf497 0%, #fdf497 5%, #fd5949 45%, #d6249f 60%, #285AEB 90%); /* Instagram gradient */
        box-shadow: 0 3px 8px rgba(0, 0, 0, 0.3); /* Clearer shadow */
    }


    @media (max-width: 768px) { /* دي معناها: طبق التعديلات دي لو عرض الشاشة 768 بكسل أو أقل */
        .container {
            margin: 20px auto; /* قلل الهامش العلوي والسفلي شوية */
            padding: 0 15px; /* قلل الـ padding الجانبي عشان تستغل مساحة أكبر */
        }

        header {
            padding-top: 40px; /* قلل المسافة العلوية في الهيدر */
            margin-bottom: 30px;
        }

        header h1 {
            font-size: 2em; /* صغر حجم عنوان "Drive Shnawy" شوية */
        }

        .dark-mode-toggle {
            top: 10px;
            left: 10px;
            padding: 8px 12px; /* صغر زر التبديل */
            font-size: 0.9em;
        }

        .sallu-message {
            top: 10px;
            right: 10px;
            font-size: 1em; /* صغر حجم نص "صلي علي محمد" */
        }

        .subject-section {
            padding: 20px; /* قلل الـ padding في أقسام المواد */
            margin-bottom: 30px;
        }

        .subject-section h2 {
            font-size: 2em; /* صغر حجم عناوين المواد */
            margin-bottom: 20px;
        }

        .subject-section h2::after {
            width: 80px; /* صغر الخط اللي تحت عنوان المادة */
            margin-top: 15px;
        }

        .teacher-card {
            padding: 20px; /* قلل الـ padding في بطاقات المعلمين */
            margin-bottom: 25px;
        }

        .teacher-card h3 {
            font-size: 1.6em; /* صغر حجم اسم المعلم */
            margin-bottom: 20px;
            padding-bottom: 10px;
        }

        .folder-section {
            padding: 15px; /* قلل الـ padding في أقسام الفولدرات */
            margin-bottom: 20px;
        }

        .folder-section h4 {
            font-size: 1.3em; /* صغر حجم عنوان الفولدر */
            padding-right: 30px;
        }

        .folder-section h4::before {
            font-size: 1.1em;
            margin-left: 8px;
        }

        .video-link {
            padding: 12px 15px; /* صغر الـ padding للينكات الفيديو */
            font-size: 0.95em; /* صغر حجم الخط للينكات الفيديو */
        }

        .video-link::before {
            font-size: 1.1em;
            margin-left: 10px;
        }

        .subject-selector {
            padding-left: 15px; /* قلل الـ padding في محدد المواد */
            margin-bottom: 30px;
            text-align: center; /* خلي الـ selector في النص عشان شكله يكون أفضل على الموبايل */
        }

        .subject-selector label {
            display: block; /* خلي الـ label ياخد سطر لوحده */
            margin-bottom: 10px; /* اعمل مسافة بين الـ label والـ select */
            font-size: 1.2em;
            margin-right: 0; /* الغي الـ margin اللي على اليمين */
        }

        .subject-selector select {
            width: 90%; /* خلي الـ select ياخد عرض كبير من الشاشة */
            max-width: 300px; /* حد أقصى لعرض الـ select */
            padding: 10px 15px;
            font-size: 1em;
            background-position: right 10px center; /* عدّل مكان السهم */
            padding-right: 35px; /* عدّل المساحة اللي على اليمين للسهم */
        }

        .quran-verse {
            font-size: 1.5em; /* صغر حجم آية القرآن */
            line-height: 1.8;
            margin-top: 40px;
            margin-bottom: 10px;
        }
        .quran-verse .verse-info {
            font-size: 0.5em; /* Even smaller for mobile */
        }

        .signature-section {
            font-size: 0.9em;
            margin-bottom: 40px;
        }
        .signature-section .name-signature {
            font-size: 1em;
        }

        .success-message {
            font-size: 1.8em; /* صغر حجم رسالة "بالتوفيق" */
            margin-top: 15px;
            margin-bottom: 40px;
        }

        footer {
            padding-top: 20px;
            padding-bottom: 15px;
        }

        .footer-social-section {
            position: static; /* رجع الـ position لـ static عشان ما يبقاش فيه تداخل */
            flex-direction: column; /* جعل الروابط تتراص عموديا */
            gap: 10px; /* تقليل المسافة بين الروابط */
            margin-top: 20px; /* اعمل مسافة بينها وبين الكلام اللي فوق */
            right: auto; /* الغي التعديلات القديمة */
            bottom: auto; /* الغي التعديلات القديمة */
            padding-left: 0;
            padding-right: 0;
        }

        .footer-social-link {
            justify-content: center; /* خلي الأيقونة والنص في منتصف الـ div */
        }
    }
  </style>
</head>
<body class="dark-mode">

  <div class="container">
    <header>
      <button class="dark-mode-toggle" onclick="toggleDarkMode()" id="darkModeToggle">Light Mode</button>
      <h1>Drive Shnawy</h1>
      <p class="sallu-message">صلي علي محمد</p>
    </header>

    <div class="subject-selector">
        <label for="subjectSelect">اختر المادة:</label>
        <select id="subjectSelect" onchange="showSubject()">
            <option value="arabic">اللغة العربية</option>
            <option value="physics">الفيزياء</option>
            <option value="chemistry">الكيمياء</option>
            <option value="biology">الأحياء</option>
            <option value="math">الرياضيات</option>
            <option value="history">التاريخ</option>
            <option value="geography">الجغرافيا</option>
            <option value="exams">الامتحانات</option>
        </select>
    </div>

    <div class="subject-section" id="arabic-section">
      <h2>اللغة العربية</h2>

      <div class="teacher-card">
        <h3>الأستاذ محمد صلاح</h3>

        <div class="folder-section">
          <h4>لايفات ليالي الامتحان</h4>
          <a class="video-link" href="https://www.youtube.com/live/OHBn1ufL2F8?si=ovdj53NeP7Qj125q" target="_blank">لايف الأسبوع الأول</a>
          <a class="video-link" href="https://www.youtube.com/live/my9fJnyM8lg?si=gGKEgS7CJL4IKhVO" target="_blank">لايف الأسبوع الثاني</a>
          <a class="video-link" href="https://www.youtube.com/live/RNr1pDMnVOw?si=X3jzGq51QG_OmMDV" target="_blank">لايف الأسبوع الرابع</a>
          <a class="video-link" href="https://www.youtube.com/live/BDCgr_U5yPY?si=NySDaW2zRmIPItMg" target="_blank">لايف الأسبوع الخامس</a>
        </div>
        <div class="folder-section">
          <h4>مراجعات ليالي الامتحان</h4>
          <a class="video-link" href="https://youtu.be/OKfhdW5FZeQ?si=6bXf_5fmFw0eN3q1" target="_blank">قصة الأيام</a>
          <a class="video-link" href="https://youtu.be/oWIECLrM8NQ?si=pk2BeQfWB3o0UbFw" target="_blank">مراجعة البلاغة</a>
          <a class="video-link" href="https://youtu.be/ngZuAuvPZ5E?si=F2UmIkwHgjpf6N1g" target="_blank">مراجعة التعبير</a>
          <a class="video-link" href="https://youtu.be/kAv13VhoWNA?si=SuJB0IVlVKhABFMf" target="_blank">النصوص والقراءة المتحررة</a>
          <a class="video-link" href="https://youtu.be/7SCtjdmpGp4?si=OfmbmxlIk1PnmL3M" target="_blank">مراجعة الأدب</a>
          <a class="video-link" href="https://youtu.be/4PERMUewA18?si=BplrpoLlIiaqJltc" target="_blank">خلاصة الأدب كامل</a>
          <a class="video-link" href="https://youtu.be/CB1mCrgngcI?si=ZjHjRVXvCC8OKEWe" target="_blank">مراجعة النحو الأولى</a>
          <a class="video-link" href="https://youtu.be/Q50l6ppl6LI?si=RLqIXT_5P0Eyu6Rw" target="_blank">مراجعة النحو الثانية</a>
          <a class="video-link" href="https://youtu.be/njNWPciL2G8?si=cBhb8_NzuWZXZLS2" target="_blank">مراجعة النحو الثالثة</a>
          <a class="video-link" href="https://youtu.be/zvIU4yYYf4k?si=Jyjt9qsPAEPwqjN0" target="_blank">مراجعة النحو الرابعة</a>
          <a class="video-link" href="https://youtu.be/i8Gp6CZKs7g?si=fQKkWr6WaDeLnbBJ" target="_blank">خلاصة النحو كامل</a>
          <a class="video-link" href="https://www.youtube.com/live/iZsvEBH1m6o?si=2uCjYEp3_caNhasq" target="_blank">آخر لايف لغة عربية</a>
          <a class="video-link" href="https://www.youtube.com/live/vgBOdrcSARQ?si=fhKO9G9EBmyURv0R" target="_blank">محاكاة امتحان ثانوية عامة</a>
        </div>
      </div>
    </div>

    <div class="subject-section" id="physics-section">
      <h2>الفيزياء</h2>

      <div class="teacher-card">
        <h3>الأستاذ محمود مجدي</h3>

        <div class="folder-section">
          <h4>الفيزياء الكهربية</h4>
          <a class="video-link" href="https://youtu.be/RSkf0nQUg7c?si=yZPjc38gSsopoRyO" target="_blank">ورشة الفصل الأول</a>
          <a class="video-link" href="https://youtu.be/j2RyGmar184?si=3dulFdOKQAU5i0iy" target="_blank">ورشة الفصل الثاني</a>
          <a class="video-link" href="https://youtu.be/RyVR_jL3LKM?si=HCgHCnIh8-DJKaW9" target="_blank">أهم 100 فكرة على الفصل الثاني</a>
          <a class="video-link" href="https://youtu.be/Wv_fusu7KzU?si=vf9DMN3VEtHsM8V4" target="_blank">مراجعة الفصل الأول والثاني</a>
          <a class="video-link" href="https://youtu.be/Ndq9UtTiZDA?si=kVRPVNbq4SbuH2DV" target="_blank">مراجعة الفصل الثالث</a>
          <a class="video-link" href="https://youtu.be/EQkAwTreJ4Q?si=2F0PkHQ_S9Sd0fMu" target="_blank">فيديو آخر للفصل الثالث</a>
          <a class="video-link" href="https://youtu.be/wJRF5_YotXI?si=3XgbocuPrG8f0vOM" target="_blank">مراجعة الفصل الرابع</a>
          <a class="video-link" href="https://youtu.be/bpPZZJ_Xth4?si=4TAcNCSsEq2E-VJL" target="_blank">مراجعة الفصل الثالث والرابع</a>
        </div>

        <div class="folder-section">
          <h4>الفيزياء الحديثة</h4>
          <a class="video-link" href="https://youtu.be/3Y-5ekyKKsk?si=AO2HfEU1xzDV3qBm" target="_blank">الفصل الخامس والسادس</a>
          <a class="video-link" href="https://youtu.be/cfg7klb__4s?si=LGNu9qk697GS030P" target="_blank">الفصل السابع والثامن</a>
          <a class="video-link" href="https://youtu.be/JrnU1rBrqac?si=wi1kPmrjFd72iR9v" target="_blank">مراجعة الحديثة كاملة</a>
        </div>
      </div>
      <div class="teacher-card">
        <h3>الأستاذ كيرلس</h3>

        <div class="folder-section">
          <h4>الفصل الأول كامل شرح وافي</h4>
          <a class="video-link" href="https://youtu.be/mb_oNRA1qOc?si=RtOQF8IQT-RFrWAt" target="_blank">الفصل الأول كامل شرح وافي</a>
          <a class="video-link" href="https://youtu.be/783r-RglOoA?si=YfQ4LojqKdb0EYDl" target="_blank">قوانين ومسائل الفصل الثاني</a>
          <a class="video-link" href="https://youtu.be/5dBJOAjTJjg?si=q52G2FkaNn7qIDb2" target="_blank">نصف الكهربية Ch1, Ch2</a>
          <a class="video-link" href="https://youtu.be/0pU2nf9wss4?si=ozLKRauANr_qilWF" target="_blank">الدينامو كامل</a>
          <a class="video-link" href="https://youtu.be/Zac93zbvjHE?si=8t_HUusJm8sHUdI5" target="_blank">حل الفصل الثالث كتاب نيوتن</a>
          <a class="video-link" href="https://youtu.be/ANH57mbAPOg?si=HBqRkvn23vOqrtdC" target="_blank">الفصل الرابع</a>
        </div>

        <div class="folder-section">
          <h4>الفيزياء الحديثة</h4>
          <a class="video-link" href="https://youtu.be/EenM0wulIBU?si=_CLB4WHpf3QePMwj" target="_blank">مسارات الفصل الخامس والسادس</a>
          <a class="video-link" href="https://youtu.be/pUJOFgMA75k?si=qVsfis5VUnrAB3vZ" target="_blank">مسارات الفصل السابع والثامن</a>
        </div>
      </div>

      <div class="teacher-card">
        <h3>الأستاذ محمد عبد المعبود</h3>

        <div class="folder-section">
          <h4>الفيزياء الكهربية</h4>
          <a class="video-link" href="https://youtu.be/Ix2Q_GdihIc?si=RLvYHu98Y-L0R5sL" target="_blank">الفصل الأول</a>
          <a class="video-link" href="https://youtu.be/xhNKYMS85To?si=Z97akQYCZ2Eg7h9D" target="_blank">الفصل الثاني</a>
          <a class="video-link" href="https://youtu.be/Sa2vI6gz6mQ?si=7QJ9VRpmBqkVxbwH" target="_blank">الفصل الثالث</a>
          <a class="video-link" href="https://youtu.be/7JuJDsOIWzI?si=UAkxsWsbGQv-z81Q" target="_blank">الفصل الرابع</a>
          <a class="video-link" href="https://youtu.be/UeQOC3sKnZ8?si=3CLhlbTw9wSoA9Sb" target="_blank">الكهربية كاملة</a>
        </div>

        <div class="folder-section">
          <h4>الفيزياء الحديثة</h4>
          <a class="video-link" href="https://youtu.be/KwhzBUtTPVk?si=iBRh6F8erxtW0hZJ" target="_blank">مراجعة الحديثة كاملة</a>
        </div>
      </div>
    </div>

    <div class="subject-section" id="chemistry-section">
      <h2>الكيمياء</h2>

      <div class="teacher-card">
        <h3>الأستاذ خالد صقر</h3>

        <div class="folder-section">
          <h4>الكيمياء العامة</h4>
          <a class="video-link" href="https://www.youtube.com/live/1gVf97MhNpc?si=xwvV7bdVPY0zt2TQ" target="_blank">الباب الأول</a>
          <a class="video-link" href="https://youtu.be/z6KuIpvEW9E?si=6v8c2f_EoK6ty1cW" target="_blank">الباب الثاني</a>
          <a class="video-link" href="https://youtu.be/xqWuGtg5wvk?si=3-K1iIBJAWuYnSuE" target="_blank">الباب الثالث</a>
          <a class="video-link" href="https://youtu.be/5nL6JUGNPJg?si=flj7TY3wCSfIwYIR" target="_blank">الباب الرابع</a>
          <a class="video-link" href="https://youtu.be/N4-lXMn9GKQ?si=UScRqH2CVyGoNzjO" target="_blank">مراجعة كاملة ليلة الامتحان</a>
        </div>

        <div class="folder-section">
          <h4>الكيمياء العضوية</h4>
          <a class="video-link" href="https://youtu.be/KVNmGA1fkMY?si=CPOyJVenoY5mPuL-" target="_blank">الفيديو الأول</a>
          <a class="video-link" href="https://youtu.be/c85ja28dRfM?si=AWgPxm7FQiRl5DB2" target="_blank">الفيديو الثاني</a>
        </div>
      </div>

      <div class="teacher-card">
        <h3>الأستاذ محمد عبد الجواد</h3>

        <div class="folder-section">
          <h4>الكيمياء العامة</h4>
          <a class="video-link" href="https://youtu.be/z_kWMm-atu4?si=GF8EJpDfbqkdBGiJ" target="_blank">الباب الأول</a>
          <a class="video-link" href="https://youtu.be/VcC2MrVu4tc?si=lpEmxiNQZnPMkyZp" target="_blank">الباب الثاني</a>
          <a class="video-link" href="https://youtu.be/-7VGiQfneZA?si=ls1NFSzIs5B6EMWR" target="_blank">أفكار على الاتزان</a>
          <a class="video-link" href="https://youtu.be/9IPMyJCzq9I?si=BNGgoly3ikNdPcWc" target="_blank">الباب الثالث كامل</a>
          <a class="video-link" href="https://youtu.be/I6Na5Jo9wCc?si=v63PdhnH-iu1NUyl" target="_blank">الباب الرابع</a>
        </div>

        <div class="folder-section">
          <h4>الكيمياء العضوية</h4>
          <a class="video-link" href="https://youtu.be/M1BoKn0aHD8?si=tPj56_zK0Q5ArUEd" target="_blank">أفكار على العضوية</a>
          <a class="video-link" href="https://youtu.be/0KTo-rHvMgc?si=we2Zp0IQUoZUcPQo" target="_blank">حتي الهيدروكربونات الحلقية</a>
          <a class="video-link" href="https://youtu.be/0KTo-rHvMgc?si=we2Zp0IQUoZUcPQo" target="_blank">من الهيدروكربونات حتى الإسترات</a>
        </div>
      </div>
    </div>

    <div class="subject-section" id="biology-section">
      <h2>الأحياء</h2>

      <div class="teacher-card">
        <h3>الأستاذ أحمد الجوهري ومحمد أيمن</h3>

        <div class="folder-section">
          <h4>فصل الدعامة والحركة</h4>
          <a class="video-link" href="https://youtu.be/Znzxkh3Di0c?si=VWzXwt-vlw-XOPg5" target="_blank">فصل الدعامة والحركة</a>
          <a class="video-link" href="https://www.youtube.com/live/wii8Z4s34j4?si=AQMtvwrpbXPrKE4b" target="_blank">لايف مراجعة الدعامة والحركة</a>
        </div>

        <div class="folder-section">
          <h4>فصل الهرمونات</h4>
          <a class="video-link" href="https://youtu.be/pfIA5atVFvY?si=jnwZ3qvcGhQK6Hif" target="_blank">فصل الهرمونات</a>
          <a class="video-link" href="https://www.youtube.com/live/3DEfFfLpOIs?si=LjRBeoJHSK4Ytxb8" target="_blank">لايف الهرمونات</a>
        </div>

        <div class="folder-section">
          <h4>فصل التكاثر</h4>
          <a class="video-link" href="https://youtu.be/OYfUt5cTIyc?si=iDdlmkkTEYTQm7iW" target="_blank">فصل التكاثر</a>
          <a class="video-link" href="https://youtu.be/NkikByv-PiY?si=XC5N1Xaac2VcXpzh" target="_blank">معسكر التكاثر</a>
        </div>

        <div class="folder-section">
          <h4>فصل المناعة</h4>
          <a class="video-link" href="https://youtu.be/D5WE0XEbRJc?si=RoeUO3nH3q-lNLrE" target="_blank">فصل المناعة</a>
          <a class="video-link" href="https://youtu.be/6DmjBsURLOs?si=rG9npq1hGuHu1G48" target="_blank">فديو تاني للمناعة</a>
        </div>

        <div class="folder-section">
          <h4>البيولوجيا الجزئية</h4>
          <a class="video-link" href="https://youtu.be/a6STbhLeKa8?si=JgRPp2NGrk5gtNt-" target="_blank">البيولوجيا الجزئية للجوهري</a>
          <a class="video-link" href="https://youtu.be/MYH27VxggVs?si=fWV0SlATfj8C8Uq6" target="_blank">البيولوجيا الجزئية محمد ايمن</a>
        </div>

        <div class="folder-section">
          <h4>الأحياء وعلوم الأرض</h4>
          <a class="video-link" href="https://youtube.com/playlist?list=PLr2gW9Zt509tgYmRJEer-iBpd4g2RRGEb&amp;si=3ACmwQ7MkSfAwa3i" target="_blank">الأحياء وعلوم الأرض محمد ايمن</a>
        </div>
      </div>
    </div>

    <div class="subject-section" id="math-section">
      <h2>الرياضة</h2>

      <div class="teacher-card">
        <h3>الأستاذ أحمد عصام</h3>

        <div class="folder-section">
          <h4>ديناميكا</h4>
          <a class="video-link" href="https://youtu.be/gz1FVTTJrVI?si=XZ8qG__OI6MY6B9L" target="_blank">مراجعة الديناميكا</a>
          <a class="video-link" href="https://www.youtube.com/live/EOcwUUCgZkc?si=VLoIaWSDc_gGah3R" target="_blank">ربط الديناميكا ببعض</a>
          <a class="video-link" href="https://youtu.be/K8jRp11zNq0?si=xnta5LT9wixetDD8" target="_blank">حل امتحانات ديناميكا Part 1</a>
          <a class="video-link" href="https://youtu.be/FkirouCuLWA?si=sISbnEBtTP4qOidC" target="_blank">حل امتحانات ديناميكا Part 2</a>
        </div>

        <div class="folder-section">
          <h4>استاتيكا</h4>
          <a class="video-link" href="https://youtu.be/on6n5qTzXC0?si=vgozdfWdCSkAcOWl" target="_blank">مراجعة الاستاتيكا</a>
          <a class="video-link" href="https://youtu.be/ogbgcfy5Rs4?si=VCoFK9AfQz-LXMuK" target="_blank">حل استاتيكا 21.22 دور اول وتاني</a>
          <a class="video-link" href="https://youtu.be/68bp8NkqC6U?si=KhiGBcDt4nK_vBKo" target="_blank">حل كمان 5 امتحانات استاتيكا</a>
        </div>

        <div class="folder-section">
          <h4>فراغية</h4>
          <a class="video-link" href="https://youtu.be/MNbYs6-7PXg?si=qmL5WfX5ZvDusVGr" target="_blank">الوحدة الاولي فراغية</a>
          <a class="video-link" href="https://youtu.be/P-SXNZ7uyQc?si=HjJVJ4vnrnU-bTNK" target="_blank">الوحدة التانية فراغية</a>
          <a class="video-link" href="https://youtu.be/moNunpGzkHE?si=FHh1ovaOGZj_fqcV" target="_blank">ملخص الجبر والفراغية</a>
        </div>

         <div class="folder-section">
          <h4>تفاضل وتكامل</h4>
          <a class="video-link" href="https://youtu.be/yApdqmyOoLE?si=NqicNEs8Q5aSfLU5" target="_blank">التفاضل والتكامل</a>
          <a class="video-link" href="https://youtu.be/qeUXsgNheyU?si=m7c9AWxp4ov7AG5b" target="_blank">حل 5 امتحانات تفاضل وتكامل</a>
           <a class="video-link" href="https://youtu.be/bsGaBGKnyos?si=pi-0joAFYSZDhsfU" target="_blank">حل 50 سؤال بيراجعوا عالفرع كامل</a>
        </div>

         <div class="folder-section">
          <h4>لايفات</h4>
          <a class="video-link" href="https://youtube.com/playlist?list=PLxFomjVnQjuSeFXAZHF3nSMUlHu9JEcC_&amp;si=XaL6e-9h6a2VCBjx" target="_blank">لايفات الرياضة 2024 كاملة</a>
        </div>

         <div class="folder-section">
          <h4>احصاء</h4>
          <a class="video-link" href="https://youtube.com/playlist?list=PLxFomjVnQjuSBI-c7cPzVyXQLjbTXNc4_&amp;si=zswiyoEL-ZOez55q" target="_blank">احصاء 2025</a>
        </div>
      </div>
    </div>

    <div class="subject-section" id="history-section">
      <h2>التاريخ</h2>

      <div class="teacher-card">
        <h3>مراجعات التاريخ</h3>

        <div class="folder-section">
          <h4>مراجعة الفصول</h4>
          <a class="video-link" href="https://youtu.be/jSE_iRkWk3s?si=Y_QSb5K2xagZKozX" target="_blank">مراجعة الفصل الأول</a>
          <a class="video-link" href="https://youtu.be/6XaBF9pqIoI?si=p_BpRlm6LTZgsmlw" target="_blank">الفصل الثاني</a>
          <a class="video-link" href="https://youtu.be/W7tBXun8MIg?si=-uQ3ok35lSnLkAe1" target="_blank">الفصل الثالث</a>
          <a class="video-link" href="https://youtu.be/QzucP1COl4w?si=6RRsvfw3hNkdyEVC" target="_blank">الفصل الرابع</a>
          <a class="video-link" href="https://youtu.be/VqsnUQt6_7E?si=JUUZeyXcyrOV31zX" target="_blank">الفصل الخامس</a>
          <a class="video-link" href="https://youtu.be/RIfa32FacHs?si=tTE6iwLXoZQ5e_Gm" target="_blank">الفصل السادس</a>
          <a class="video-link" href="https://youtu.be/1KZJMlldHvw?si=3dZKz0TFFruiFoSV" target="_blank">الفصل السابع</a>
          <a class="video-link" href="https://youtu.be/FHkB9rJZ6rg?si=EGzsI0m-lcdopfty" target="_blank">الفصل الثامن</a>
        </div>
      </div>
    </div>

    <div class="subject-section" id="geography-section">
      <h2>الجغرافيا</h2>

      <div class="teacher-card">
        <h3>مراجعات الجغرافيا</h3>

        <div class="folder-section">
          <h4>مراجعة الوحدات</h4>
          <a class="video-link" href="https://youtu.be/4PERMUewA18?si=BplrpoLlIiaqJltc5" target="_blank">مراجعة الوحدة الأولى</a>
          <a class="video-link" href="https://youtu.be/4PERMUewA18?si=BplrpoLlIiaqJltc6" target="_blank">مراجعة الوحدة الثانية</a>
          <a class="video-link" href="https://youtu.be/4PERMUewA18?si=BplrpoLlIiaqJltc7" target="_blank">مراجعة الوحدة الثالثة</a>
          <a class="video-link" href="https://youtu.be/4PERMUewA18?si=BplrpoLlIiaqJltc8" target="_blank">مراجعة الوحدة الرابعة</a>
        </div>
      </div>
    </div>

    <div class="subject-section" id="exams-section">
      <h2>الامتحانات</h2>
      <div class="teacher-card">
        <h3>امتحانات الثانوية العامة</h3>
        <div class="folder-section">
          <h4>امتحانات الثانوية العامة حتى 2024</h4>
          <a class="video-link exams-link" href="https://drive.google.com/drive/folders/1F5RWV24f0xdmLCjWdTCnnWM4Ml7kswZ2" target="_blank">الوصول إلى مجلد الامتحانات</a>
        </div>
      </div>
    </div>

    <div class="quran-verse">
      "وقل اعملو فسيري الله عملكم ورسوله والمؤمنون وستردون الي علم الغيب والشهدة فينبئكم بما كنتم تعملون"
      <span class="verse-info">(سوره التوبه: الايه 105)</span>
    </div>

    <div class="success-message">
      بالتوفيق
    </div>
  </div>

  <footer>
    <p>جميع الحقوق محفوظه.</p>
    <div class="signature-section">
        <p class="name-signature">BY. ENG.Ahmed Abdin</p>
        <p>Software Engineer</p>
    </div>
    <p>فولو</p>
    <div class="footer-social-section">
        <a href="https://www.facebook.com/share/1CConP7WmN/" target="_blank" class="footer-social-link">
            <span>Facebook</span>
            <svg class="social-icon-svg facebook-icon-svg" viewbox="0 0 24 24">
                <path d="M17 2H7C4.243 2 2 4.243 2 7v10c0 2.757 2.243 5 5 5h10c2.757 0 5-2.243 5-5V7c0-2.757-2.243-5-5-5zm-2.5 7h-2v2h2v3h-3v-3h-2v-2h2V7c0-1.657 1.343-3 3-3h2v3h-2c-.552 0-1 .448-1 1v1h3l-.5 3z" />
            </svg>
        </a>
        <a href="https://www.instagram.com/ahmed_3bdin?igsh=MTFydWZrMDY5anBrNg==" target="_blank" class="footer-social-link">
            <span>Instagram</span>
            <svg class="social-icon-svg instagram-icon-svg" viewbox="0 0 24 24">
                <path d="M7.8 2h8.4C19.4 2 22 4.6 22 7.8v8.4c0 3.2-2.6 5.8-5.8 5.8H7.8C4.6 22 2 19.4 2 16.2V7.8C2 4.6 4.6 2 7.8 2zm-.2 2A4.2 4.2 0 003 7.6v8.8a4.2 4.2 0 004.8 4.2h8.8a4.2 4.2 0 004.2-4.2V7.6A4.2 4.2 0 0016.2 3.8H7.6zM12 7a5 5 0 100 10 5 5 0 000-10zm0 8a3 3 0 110-6 3 3 0 010 6zm5.2-9.4a1.2 1.2 0 100 2.4 1.2 1.2 0 000-2.4z" />
            </svg>
        </a>
    </div>
  </footer>

  <script>
    function toggleDarkMode() {
      const body = document.body;
      const toggleButton = document.getElementById('darkModeToggle');
      body.classList.toggle('light-mode');

      if (body.classList.contains('light-mode')) {
        toggleButton.textContent = 'Dark Mode';
        localStorage.setItem('theme', 'light');
      } else {
        toggleButton.textContent = 'Light Mode';
        localStorage.setItem('theme', 'dark');
      }
    }

    // Set theme on load
    document.addEventListener('DOMContentLoaded', () => {
      const savedTheme = localStorage.getItem('theme');
      if (savedTheme === 'light') {
        document.body.classList.add('light-mode');
        document.getElementById('darkModeToggle').textContent = 'Dark Mode';
      } else {
        document.body.classList.remove('light-mode');
        document.getElementById('darkModeToggle').textContent = 'Light Mode';
      }
      showSubject(); // Show the default subject on page load
    });

    function showSubject() {
        const selectedSubject = document.getElementById('subjectSelect').value;
        const subjectSections = document.querySelectorAll('.subject-section');

        subjectSections.forEach(section => {
            section.classList.remove('active');
        });

        const activeSection = document.getElementById(`${selectedSubject}-section`);
        if (activeSection) {
            activeSection.classList.add('active');
        }
    }
  </script>

</body></html>

- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
