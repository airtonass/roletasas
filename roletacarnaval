<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>🎭 Carnaval SAS TELECOM - Gire e Ganhe!</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700;900&family=Bungee&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        :root {
            --carnaval-yellow: #FFD700;
            --carnaval-green: #00FF7F;
            --carnaval-pink: #FF1493;
            --carnaval-purple: #9400D3;
            --carnaval-blue: #00BFFF;
            --carnaval-orange: #FF4500;
        }

        body {
            font-family: 'Poppins', sans-serif;
            background: linear-gradient(135deg, #9400D3 0%, #FF1493 25%, #FFD700 50%, #00FF7F 75%, #00BFFF 100%);
            background-size: 400% 400%;
            animation: carnival-bg 10s ease infinite;
            min-height: 100vh;
            color: white;
            overflow-x: hidden;
            position: relative;
        }

        @keyframes carnival-bg {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        /* Confetes caindo */
        .confetti-container {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: 1000;
            overflow: hidden;
        }

        .confetti {
            position: absolute;
            width: 15px;
            height: 15px;
            animation: confetti-fall linear infinite;
            opacity: 0.8;
        }

        .confetti:nth-child(1) { left: 10%; background: var(--carnaval-yellow); animation-duration: 3s; animation-delay: 0s; border-radius: 50%; }
        .confetti:nth-child(2) { left: 20%; background: var(--carnaval-pink); animation-duration: 4s; animation-delay: 0.5s; clip-path: polygon(50% 0%, 0% 100%, 100% 100%); }
        .confetti:nth-child(3) { left: 30%; background: var(--carnaval-green); animation-duration: 3.5s; animation-delay: 1s; border-radius: 0; }
        .confetti:nth-child(4) { left: 40%; background: var(--carnaval-purple); animation-duration: 4.5s; animation-delay: 1.5s; clip-path: polygon(50% 0%, 100% 50%, 50% 100%, 0% 50%); }
        .confetti:nth-child(5) { left: 50%; background: var(--carnaval-blue); animation-duration: 3s; animation-delay: 0.3s; border-radius: 50%; }
        .confetti:nth-child(6) { left: 60%; background: var(--carnaval-orange); animation-duration: 4s; animation-delay: 0.8s; clip-path: polygon(50% 0%, 0% 100%, 100% 100%); }
        .confetti:nth-child(7) { left: 70%; background: var(--carnaval-yellow); animation-duration: 3.5s; animation-delay: 1.2s; border-radius: 0; }
        .confetti:nth-child(8) { left: 80%; background: var(--carnaval-pink); animation-duration: 4.2s; animation-delay: 0.2s; clip-path: polygon(50% 0%, 100% 50%, 50% 100%, 0% 50%); }
        .confetti:nth-child(9) { left: 90%; background: var(--carnaval-green); animation-duration: 3.8s; animation-delay: 1.5s; border-radius: 50%; }
        .confetti:nth-child(10) { left: 5%; background: var(--carnaval-purple); animation-duration: 4.5s; animation-delay: 0.7s; clip-path: polygon(50% 0%, 0% 100%, 100% 100%); }

        @keyframes confetti-fall {
            0% { transform: translateY(-100px) rotate(0deg); opacity: 1; }
            100% { transform: translateY(100vh) rotate(720deg); opacity: 0.3; }
        }

        /* Serpentinas */
        .serpentina {
            position: fixed;
            width: 8px;
            height: 100px;
            border-radius: 4px;
            animation: serpentina-sway 3s ease-in-out infinite;
            z-index: 999;
            opacity: 0.6;
        }

        .serpentina:nth-child(11) { left: 5%; top: 0; background: linear-gradient(to bottom, var(--carnaval-yellow), var(--carnaval-orange)); animation-delay: 0s; }
        .serpentina:nth-child(12) { left: 15%; top: 20px; background: linear-gradient(to bottom, var(--carnaval-pink), var(--carnaval-purple)); animation-delay: 0.5s; }
        .serpentina:nth-child(13) { left: 85%; top: 0; background: linear-gradient(to bottom, var(--carnaval-green), var(--carnaval-blue)); animation-delay: 1s; }
        .serpentina:nth-child(14) { left: 95%; top: 30px; background: linear-gradient(to bottom, var(--carnaval-orange), var(--carnaval-yellow)); animation-delay: 1.5s; }

        @keyframes serpentina-sway {
            0%, 100% { transform: rotate(-5deg); }
            50% { transform: rotate(5deg); }
        }

        /* Máscaras de carnaval decorativas */
        .mask-decoration {
            position: fixed;
            font-size: 4rem;
            opacity: 0.2;
            animation: mask-float 6s ease-in-out infinite;
            z-index: 1;
        }

        .mask-decoration:nth-child(15) { top: 10%; left: 5%; animation-delay: 0s; }
        .mask-decoration:nth-child(16) { top: 20%; right: 5%; animation-delay: 2s; }
        .mask-decoration:nth-child(17) { bottom: 20%; left: 8%; animation-delay: 4s; }
        .mask-decoration:nth-child(18) { bottom: 10%; right: 10%; animation-delay: 1s; }

        @keyframes mask-float {
            0%, 100% { transform: translateY(0) rotate(-10deg); }
            50% { transform: translateY(-20px) rotate(10deg); }
        }

        header {
            padding: 20px 5%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: relative;
            z-index: 100;
            background: rgba(0, 0, 0, 0.3);
            backdrop-filter: blur(10px);
            border-bottom: 3px solid var(--carnaval-yellow);
        }

        .logo-container {
            display: flex;
            align-items: center;
            gap: 15px;
        }

        .logo-img {
            width: 80px;
            height: 80px;
            background: white;
            border-radius: 50%;
            padding: 10px;
            border: 4px solid var(--carnaval-yellow);
            box-shadow: 0 0 20px var(--carnaval-yellow);
            animation: logo-pulse 2s infinite;
        }

        @keyframes logo-pulse {
            0%, 100% { box-shadow: 0 0 20px var(--carnaval-yellow); }
            50% { box-shadow: 0 0 40px var(--carnaval-yellow), 0 0 60px var(--carnaval-pink); }
        }

        .logo-text {
            font-family: 'Bungee', cursive;
            font-size: 1.5rem;
            background: linear-gradient(135deg, var(--carnaval-yellow), var(--carnaval-pink), var(--carnaval-green));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            text-transform: uppercase;
            letter-spacing: 2px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 40px 20px;
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 60px;
            align-items: center;
            min-height: calc(100vh - 120px);
            position: relative;
            z-index: 10;
        }

        .content {
            animation: slideInLeft 1s ease-out;
            background: rgba(0, 0, 0, 0.4);
            padding: 40px;
            border-radius: 30px;
            border: 3px solid var(--carnaval-yellow);
            backdrop-filter: blur(10px);
            box-shadow: 0 0 30px rgba(255, 215, 0, 0.3);
        }

        @keyframes slideInLeft {
            from { opacity: 0; transform: translateX(-50px); }
            to { opacity: 1; transform: translateX(0); }
        }

        .badge {
            display: inline-block;
            background: linear-gradient(135deg, var(--carnaval-pink), var(--carnaval-orange));
            color: white;
            padding: 10px 25px;
            border-radius: 50px;
            font-weight: 900;
            font-size: 1rem;
            margin-bottom: 20px;
            box-shadow: 0 4px 15px rgba(255, 20, 147, 0.6);
            animation: badge-shake 1s infinite;
            text-transform: uppercase;
            letter-spacing: 1px;
            border: 2px solid white;
        }

        @keyframes badge-shake {
            0%, 100% { transform: rotate(-2deg); }
            50% { transform: rotate(2deg); }
        }

        h1 {
            font-family: 'Bungee', cursive;
            font-size: 3rem;
            font-weight: 900;
            line-height: 1.2;
            margin-bottom: 20px;
            background: linear-gradient(135deg, var(--carnaval-yellow), var(--carnaval-pink), var(--carnaval-green), var(--carnaval-blue));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            text-transform: uppercase;
            text-shadow: 3px 3px 6px rgba(0,0,0,0.5);
            animation: title-glow 2s infinite;
        }

        @keyframes title-glow {
            0%, 100% { filter: brightness(1); }
            50% { filter: brightness(1.3); }
        }

        .subtitle {
            font-size: 1.2rem;
            color: white;
            margin-bottom: 30px;
            line-height: 1.6;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
            font-weight: 600;
        }

        .prizes-list {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 15px;
            margin-bottom: 30px;
        }

        .prize-item {
            background: rgba(255, 255, 255, 0.15);
            border: 2px solid var(--carnaval-yellow);
            padding: 15px;
            border-radius: 15px;
            display: flex;
            align-items: center;
            gap: 10px;
            transition: all 0.3s ease;
            backdrop-filter: blur(5px);
            animation: prize-bounce 2s infinite;
        }

        .prize-item:nth-child(2) { animation-delay: 0.2s; }
        .prize-item:nth-child(3) { animation-delay: 0.4s; }
        .prize-item:nth-child(4) { animation-delay: 0.6s; }
        .prize-item:nth-child(5) { animation-delay: 0.8s; }

        @keyframes prize-bounce {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-5px); }
        }

        .prize-item:hover {
            transform: scale(1.05) rotate(2deg);
            border-color: var(--carnaval-pink);
            box-shadow: 0 10px 30px rgba(255, 20, 147, 0.4);
        }

        .prize-item.lose {
            border-color: #666;
            opacity: 0.7;
            animation: none;
        }

        .prize-item.special {
            border-color: var(--carnaval-green);
            background: rgba(0, 255, 127, 0.2);
            box-shadow: 0 0 20px var(--carnaval-green);
        }

        .prize-icon {
            font-size: 1.8rem;
            animation: icon-spin 3s infinite;
        }

        @keyframes icon-spin {
            0%, 100% { transform: rotate(0deg); }
            25% { transform: rotate(10deg); }
            75% { transform: rotate(-10deg); }
        }

        .prize-text {
            font-size: 0.85rem;
            font-weight: 700;
            color: white;
            text-shadow: 1px 1px 2px rgba(0,0,0,0.5);
        }

        .wheel-container {
            display: flex;
            flex-direction: column;
            align-items: center;
            animation: slideInRight 1s ease-out;
            position: relative;
        }

        @keyframes slideInRight {
            from { opacity: 0; transform: translateX(50px); }
            to { opacity: 1; transform: translateX(0); }
        }

        .wheel-wrapper {
            position: relative;
            width: 450px;
            height: 450px;
            filter: drop-shadow(0 0 30px rgba(255, 215, 0, 0.8));
        }

        .wheel {
            width: 100%;
            height: 100%;
            border-radius: 50%;
            position: relative;
            overflow: hidden;
            transition: transform 5s cubic-bezier(0.17, 0.67, 0.12, 0.99);
            border: 8px solid var(--carnaval-yellow);
            box-shadow: 0 0 50px rgba(255, 215, 0, 0.6), inset 0 0 30px rgba(0,0,0,0.5);
            background: conic-gradient(from 0deg, var(--carnaval-purple), var(--carnaval-pink), var(--carnaval-yellow), var(--carnaval-green), var(--carnaval-blue), var(--carnaval-orange), var(--carnaval-purple));
        }

        .wheel-segment {
            position: absolute;
            width: 50%;
            height: 50%;
            transform-origin: right bottom;
            left: 0;
            top: 0;
            display: flex;
            align-items: center;
            justify-content: center;
            font-weight: 900;
            font-size: 0.8rem;
            text-align: center;
            padding: 15px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.8);
            color: white;
            border: 2px solid rgba(255,255,255,0.3);
        }

        .wheel-segment span {
            transform: rotate(22.5deg);
            display: block;
            width: 100%;
            padding-left: 15px;
            line-height: 1.2;
        }

        /* 8 segmentos carnaval */
        .segment-1 { background: linear-gradient(135deg, #FF1493, #FF006E); transform: rotate(0deg); }
        .segment-2 { background: linear-gradient(135deg, #666, #444); transform: rotate(45deg); color: #ccc; }
        .segment-3 { background: linear-gradient(135deg, #00FF7F, #00CC66); transform: rotate(90deg); color: #000; }
        .segment-4 { background: linear-gradient(135deg, #666, #444); transform: rotate(135deg); color: #ccc; }
        .segment-5 { background: linear-gradient(135deg, #00BFFF, #0099CC); transform: rotate(180deg); }
        .segment-6 { background: linear-gradient(135deg, #666, #444); transform: rotate(225deg); color: #ccc; }
        .segment-7 { background: linear-gradient(135deg, #FF4500, #FF6600); transform: rotate(270deg); }
        .segment-8 { background: linear-gradient(135deg, #666, #444); transform: rotate(315deg); color: #ccc; }

        .wheel-center {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            width: 100px;
            height: 100px;
            background: linear-gradient(135deg, var(--carnaval-yellow), var(--carnaval-pink));
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-family: 'Bungee', cursive;
            font-weight: 900;
            color: #000;
            font-size: 0.7rem;
            box-shadow: 0 0 30px rgba(255, 215, 0, 0.8);
            z-index: 10;
            border: 4px solid white;
            text-align: center;
            line-height: 1.2;
            animation: center-pulse 1.5s infinite;
        }

        @keyframes center-pulse {
            0%, 100% { transform: translate(-50%, -50%) scale(1); }
            50% { transform: translate(-50%, -50%) scale(1.1); }
        }

        .pointer {
            position: absolute;
            top: -25px;
            left: 50%;
            transform: translateX(-50%);
            width: 50px;
            height: 60px;
            background: linear-gradient(135deg, var(--carnaval-yellow), var(--carnaval-orange));
            clip-path: polygon(50% 100%, 0 0, 100% 0);
            z-index: 20;
            filter: drop-shadow(0 4px 6px rgba(0,0,0,0.5));
            animation: pointer-bounce 0.5s infinite;
        }

        @keyframes pointer-bounce {
            0%, 100% { transform: translateX(-50%) translateY(0); }
            50% { transform: translateX(-50%) translateY(-5px); }
        }

        .spin-btn {
            margin-top: 40px;
            padding: 25px 70px;
            font-size: 1.5rem;
            font-family: 'Bungee', cursive;
            font-weight: 900;
            border: none;
            border-radius: 50px;
            background: linear-gradient(135deg, var(--carnaval-pink), var(--carnaval-orange), var(--carnaval-yellow));
            background-size: 200% 200%;
            color: white;
            cursor: pointer;
            box-shadow: 0 10px 30px rgba(255, 20, 147, 0.6);
            transition: all 0.3s ease;
            text-transform: uppercase;
            letter-spacing: 2px;
            position: relative;
            overflow: hidden;
            animation: btn-gradient 3s ease infinite, btn-shake 2s infinite;
            border: 3px solid white;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
        }

        @keyframes btn-gradient {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        @keyframes btn-shake {
            0%, 100% { transform: rotate(-1deg); }
            50% { transform: rotate(1deg); }
        }

        .spin-btn:hover {
            transform: scale(1.1);
            box-shadow: 0 15px 40px rgba(255, 20, 147, 0.8);
        }

        .spin-btn:disabled {
            opacity: 0.6;
            cursor: not-allowed;
            animation: none;
        }

        .modal {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0,0,0,0.8);
            z-index: 2000;
            justify-content: center;
            align-items: center;
            backdrop-filter: blur(10px);
        }

        .modal-content {
            background: linear-gradient(135deg, #9400D3, #FF1493);
            padding: 40px;
            border-radius: 30px;
            max-width: 500px;
            width: 90%;
            text-align: center;
            border: 4px solid var(--carnaval-yellow);
            box-shadow: 0 0 50px rgba(255, 215, 0, 0.6);
            animation: modalPop 0.5s ease-out;
            position: relative;
        }

        @keyframes modalPop {
            0% { transform: scale(0.5) rotate(-10deg); opacity: 0; }
            100% { transform: scale(1) rotate(0deg); opacity: 1; }
        }

        .modal-icon {
            font-size: 5rem;
            margin-bottom: 20px;
            animation: icon-bounce 1s infinite;
        }

        @keyframes icon-bounce {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.3); }
        }

        .modal h2 {
            font-family: 'Bungee', cursive;
            font-size: 2.2rem;
            margin-bottom: 15px;
            color: var(--carnaval-yellow);
            text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
        }

        .modal p {
            color: white;
            margin-bottom: 30px;
            font-size: 1.2rem;
            font-weight: 600;
            text-shadow: 1px 1px 2px rgba(0,0,0,0.5);
        }

        .form-group {
            margin-bottom: 20px;
            text-align: left;
        }

        .form-group label {
            display: block;
            margin-bottom: 8px;
            font-weight: 700;
            color: var(--carnaval-yellow);
            text-transform: uppercase;
            font-size: 0.9rem;
        }

        .form-group input,
        .form-group select {
            width: 100%;
            padding: 15px;
            border: 3px solid var(--carnaval-yellow);
            border-radius: 15px;
            background: rgba(255,255,255,0.9);
            color: #333;
            font-size: 1rem;
            font-weight: 600;
            transition: all 0.3s ease;
        }

        .form-group input:focus,
        .form-group select:focus {
            outline: none;
            border-color: var(--carnaval-pink);
            box-shadow: 0 0 20px rgba(255, 20, 147, 0.5);
            transform: scale(1.02);
        }

        .submit-btn {
            width: 100%;
            padding: 20px;
            background: linear-gradient(135deg, var(--carnaval-yellow), var(--carnaval-orange));
            color: #000;
            border: none;
            border-radius: 15px;
            font-size: 1.3rem;
            font-family: 'Bungee', cursive;
            font-weight: 900;
            cursor: pointer;
            transition: all 0.3s ease;
            margin-top: 10px;
            text-transform: uppercase;
            box-shadow: 0 5px 20px rgba(0,0,0,0.3);
        }

        .submit-btn:hover {
            transform: scale(1.05);
            box-shadow: 0 10px 30px rgba(255, 215, 0, 0.6);
        }

        .close-modal {
            position: absolute;
            top: 15px;
            right: 20px;
            font-size: 2.5rem;
            cursor: pointer;
            color: white;
            transition: all 0.3s;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
        }

        .close-modal:hover {
            color: var(--carnaval-yellow);
            transform: rotate(90deg);
        }

        .result-modal .modal-content {
            background: linear-gradient(135deg, #00FF7F, #00BFFF);
            border-color: white;
        }

        .result-modal.lose .modal-content {
            background: linear-gradient(135deg, #666, #444);
            border-color: #999;
        }

        .result-modal.special .modal-content {
            background: linear-gradient(135deg, #FF4500, #FFD700);
            border-color: white;
        }

        .prize-display {
            font-family: 'Bungee', cursive;
            font-size: 2rem;
            margin: 20px 0;
            animation: prize-bounce-display 1s infinite;
            font-weight: 900;
            line-height: 1.2;
            color: white;
            text-shadow: 3px 3px 6px rgba(0,0,0,0.5);
        }

        @keyframes prize-bounce-display {
            0%, 100% { transform: scale(1) rotate(-2deg); }
            50% { transform: scale(1.1) rotate(2deg); }
        }

        .social-buttons {
            position: fixed;
            bottom: 30px;
            right: 30px;
            display: flex;
            flex-direction: column;
            gap: 15px;
            z-index: 100;
        }

        .social-btn {
            width: 65px;
            height: 65px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 2rem;
            color: white;
            text-decoration: none;
            box-shadow: 0 5px 20px rgba(0,0,0,0.4);
            transition: all 0.3s ease;
            animation: social-dance 2s infinite;
            border: 3px solid white;
        }

        .social-btn:nth-child(1) { animation-delay: 0s; }
        .social-btn:nth-child(2) { animation-delay: 1s; }

        @keyframes social-dance {
            0%, 100% { transform: rotate(0deg) scale(1); }
            25% { transform: rotate(10deg) scale(1.1); }
            75% { transform: rotate(-10deg) scale(1.1); }
        }

        .social-btn:hover {
            transform: scale(1.2) rotate(360deg);
        }

        .whatsapp-btn {
            background: linear-gradient(135deg, #25d366, #128c7e);
        }

        .instagram-btn {
            background: linear-gradient(45deg, #f09433 0%, #e6683c 25%, #dc2743 50%, #cc2366 75%, #bc1888 100%);
        }

        .loading {
            display: inline-block;
            width: 25px;
            height: 25px;
            border: 4px solid rgba(255,255,255,.3);
            border-radius: 50%;
            border-top-color: white;
            animation: spin 1s ease-in-out infinite;
        }

        @keyframes spin {
            to { transform: rotate(360deg); }
        }

        .success-message {
            background: rgba(0, 255, 127, 0.3);
            border: 3px solid var(--carnaval-green);
            color: white;
            padding: 15px;
            border-radius: 15px;
            margin-bottom: 20px;
            display: none;
            font-weight: 700;
            text-shadow: 1px 1px 2px rgba(0,0,0,0.5);
        }

        .try-again-btn {
            background: linear-gradient(135deg, #666, #444);
            color: white;
            margin-top: 10px;
        }

        @media (max-width: 968px) {
            .container {
                grid-template-columns: 1fr;
                gap: 40px;
            }

            h1 {
                font-size: 2.2rem;
            }

            .wheel-wrapper {
                width: 350px;
                height: 350px;
            }

            .wheel-segment {
                font-size: 0.7rem;
            }

            .prizes-list {
                grid-template-columns: 1fr;
            }

            .content {
                padding: 25px;
            }
        }

        @media (max-width: 480px) {
            .wheel-wrapper {
                width: 300px;
                height: 300px;
            }

            h1 {
                font-size: 1.8rem;
            }

            .social-buttons {
                bottom: 20px;
                right: 20px;
            }

            .social-btn {
                width: 55px;
                height: 55px;
                font-size: 1.5rem;
            }

            .spin-btn {
                padding: 20px 40px;
                font-size: 1.2rem;
            }
        }
    </style>
</head>
<body>
    <!-- Elementos Decorativos Carnaval -->
    <div class="confetti-container">
        <div class="confetti"></div>
        <div class="confetti"></div>
        <div class="confetti"></div>
        <div class="confetti"></div>
        <div class="confetti"></div>
        <div class="confetti"></div>
        <div class="confetti"></div>
        <div class="confetti"></div>
        <div class="confetti"></div>
        <div class="confetti"></div>
        <div class="serpentina"></div>
        <div class="serpentina"></div>
        <div class="serpentina"></div>
        <div class="serpentina"></div>
        <div class="mask-decoration">🎭</div>
        <div class="mask-decoration">🎪</div>
        <div class="mask-decoration">🎨</div>
        <div class="mask-decoration">🎭</div>
    </div>

    <header>
        <div class="logo-container">
            <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAIwAAACMCAYAAACuwEE+AAAACXBIWXMAAAsTAAALEwEAmpwYAAAF0WlUWHRYTUw6Y29tLmFkb2JlLnhtcAAAAAAAPD94cGFja2V0IGJlZ2luPSLvu78iIGlkPSJXNU0wTXBDZWhpSHpyZVN6TlRjemtjOWQiPz4gPHg6eG1wbWV0YSB4bWxuczp4PSJhZG9iZTpuczptZXRhLyIgeDp4bXB0az0iQWRvYmUgWE1QIENvcmUgNS42LWMxNDIgNzkuMTY0MzUyLCAyMDE3LzA4LzIzLTA5OjU2OjQ3ICAgICAgICAiPiA8cmRmOlJERiB4bWxuczpyZGY9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkvMDIvMjItcmRmLXN5bnRheC1ucyMiPiA8cmRmOkRlc2NyaXB0aW9uIHJkZjphYm91dD0iIiB4bWxuczp4bXA9Imh0dHA6Ly9ucy5hZG9iZS5jb20veGFwLzEuMC8iIHhtbG5zOnhtcE1NPSJodHRwOi8vbnMuYWRvYmUuY29tL3hhcC8xLjAvbW0vIiB4bWxuczpzdEV2dD0iaHR0cDovL25zLmFkb2JlLmNvbS94YXAvMS4wL3NUeXBlL1Jlc291cmNlRXZlbnQjIiB4bWxuczpkYz0iaHR0cDovL3B1cmwub3JnL2RjL2VsZW1lbnRzLzEuMS8iIHhtbG5zOnBob3Rvc2hvcD0iaHR0cDovL25zLmFkb2JlLmNvbS9waG90b3Nob3AvMS4wLyIgeG1wOkNyZWF0b3JUb29sPSJBZG9iZSBQaG90b3Nob3AgQ0MgMjAxOCAoV2luZG93cykiIHhtcDpDcmVhdGVEYXRlPSIyMDIzLTAzLTE1VDEwOjMwOjAwLTAzOjAwIiB4bXA6TWV0YWRhdGFEYXRlPSIyMDIzLTAzLTE1VDEwOjMwOjAwLTAzOjAwIiB4bXA6TW9kaWZ5RGF0ZT0iMjAyMy0wMy0xNVQxMDozMDowMC0wMzowMCIgeG1wTU06SW5zdGFuY2VJRD0ieG1wLmlpZDozMGEyYjI0Zi1iMzQ0LTQ3NDItYjI0Zi0zMGEyYjI0ZmIzNDQiIHhtcE1NOkRvY3VtZW50SUQ9ImFkb2JlOmRvY2lkOnBob3Rvc2hvcDozMGEyYjI0Zi1iMzQ0LTQ3NDItYjI0Zi0zMGEyYjI0ZmIzNDQiIHhtcE1NOk9yaWdpbmFsRG9jdW1lbnRJRD0ieG1wLmRpZDozMGEyYjI0Zi1iMzQ0LTQ3NDItYjI0Zi0zMGEyYjI0ZmIzNDQiIGRjOmZvcm1hdD0iaW1hZ2UvcG5nIiBwaG90b3Nob3A6Q29sb3JNb2RlPSIzIj4gPHhtcE1NOkhpc3Rvcnk+IDxyZGY6U2VxPiA8cmRmOmxpIHN0RXZ0OmFjdGlvbj0iY3JlYXRlZCIgc3RFdnQ6aW5zdGFuY2VJRD0ieG1wLmlpZDozMGEyYjI0Zi1iMzQ0LTQ3NDItYjI0Zi0zMGEyYjI0ZmIzNDQiIHN0RXZ0OndoZW49IjIwMjMtMDMtMTVUMTA6MzA6MDAtMDM6MDAiIHN0RXZ0OnNvZnR3YXJlQWdlbnQ9IkFkb2JlIFBob3Rvc2hvcCBDQyAyMDE4IChXaW5kb3dzKSIvPiA8L3JkZjpTZXE+IDwveG1wTU06SGlzdG9yeT4gPC9yZGY6RGVzY3JpcHRpb24+IDwvcmRmOlJERj4gPC94OnhtcG1ldGE+IDw/eHBhY2tldCBlbmQ9InIiPz4B//79/Pv6+fj39vX08/Lx8O/u7ezr6uno5+bl5OPi4eDf3t3c29rZ2NfW1dTT0tHQz87NzMvKycjHxsXEw8LBwL++vby7urm4t7a1tLOysbCvrq2sq6qpqKempaSjoqGgn56dnJuamZiXlpWUk5KRkI+OjYyLiomIh4aFhIOCgYB/fn18e3p5eHd2dXRzcnFwb25tbGtqaWhnZmVkY2JhYF9eXVxbWllYV1ZVVFNSUVBPTk1MS0pJSEdGRURDQkFAPz49PDs6OTg3NjU0MzIxMC8uLSwrKikoJyYlJCMiISAfHh0cGxoZGBcWFRQTEhEQDw4NDAsKCQgHBgUEAwIBAAAh+QQBAAABACwAAAAAFQAJAAACF4yPgMsJ2mJ4VDKKrd4GVz5lYPeMiVUAADs=" alt="S.A.S TELECOM Logo" class="logo-img">
            <div class="logo-text">S.A.S<br>TELECOM</div>
        </div>
    </header>

    <div class="container">
        <div class="content">
            <div class="badge">🎭 É Carnaval na SAS!</div>
            <h1>Gire e<br>Ganhe! 🎉</h1>
            <p class="subtitle">A folia chegou na SAS TELECOM! 🎊 Gire a roleta carnavalesca e concorra a prêmios incríveis! 🎁✨</p>
            
            <div class="prizes-list">
                <div class="prize-item">
                    <div class="prize-icon">🎁</div>
                    <div class="prize-text">1 Mês de Internet Grátis</div>
                </div>
                <div class="prize-item special">
                    <div class="prize-icon">💚</div>
                    <div class="prize-text">Primeiro Mês por R$5</div>
                </div>
                <div class="prize-item">
                    <div class="prize-icon">🏷️</div>
                    <div class="prize-text">3 Meses com 50% OFF</div>
                </div>
                <div class="prize-item">
                    <div class="prize-icon">🔄</div>
                    <div class="prize-text">Gire Novamente</div>
                </div>
                <div class="prize-item lose">
                    <div class="prize-icon">😢</div>
                    <div class="prize-text">Não foi dessa vez (3x)</div>
                </div>
            </div>
        </div>

        <div class="wheel-container">
            <div class="wheel-wrapper">
                <div class="pointer"></div>
                <div class="wheel" id="wheel">
                    <div class="wheel-segment segment-1"><span>1 Mês<br>Grátis 🎁</span></div>
                    <div class="wheel-segment segment-2"><span>Não foi<br>dessa vez</span></div>
                    <div class="wheel-segment segment-3"><span>1º Mês<br>R$5 💚</span></div>
                    <div class="wheel-segment segment-4"><span>Não foi<br>dessa vez</span></div>
                    <div class="wheel-segment segment-5"><span>3 Meses<br>50% OFF 🏷️</span></div>
                    <div class="wheel-segment segment-6"><span>Não foi<br>dessa vez</span></div>
                    <div class="wheel-segment segment-7"><span>Gire<br>Novamente 🔄</span></div>
                    <div class="wheel-segment segment-8"><span>Não foi<br>dessa vez</span></div>
                </div>
                <div class="wheel-center">S.A.S<br>TELECOM</div>
            </div>
            
            <button class="spin-btn" id="spinBtn" onclick="openModal()">
                🎰 GIRAR ROLETA 🎰
            </button>
        </div>
    </div>

    <!-- Registration Modal -->
    <div class="modal" id="registerModal">
        <div class="modal-content">
            <span class="close-modal" onclick="closeModal()">&times;</span>
            <div class="modal-icon">🎭</div>
            <h2>Entre na Folia!</h2>
            <p>Preencha seus dados para participar do carnaval da SAS TELECOM:</p>
            
            <div class="success-message" id="successMessage">
                ✅ Dados salvos! Preparando a roleta carnavalesca...
            </div>

            <form id="registerForm" onsubmit="startSpin(event)">
                <div class="form-group">
                    <label for="nome">🎭 Nome Completo</label>
                    <input type="text" id="nome" required placeholder="Digite seu nome">
                </div>
                
                <div class="form-group">
                    <label for="telefone">📱 WhatsApp</label>
                    <input type="tel" id="telefone" required placeholder="(85) 99999-9999" maxlength="15">
                </div>
                
                <div class="form-group">
                    <label for="endereco">📍 Endereço</label>
                    <input type="text" id="endereco" required placeholder="Rua, número, bairro">
                </div>
                
                <div class="form-group">
                    <label for="plano">🌐 Plano de Interesse</label>
                    <select id="plano" required>
                        <option value="">Selecione um plano</option>
                        <option value="200mb">🚀 200 Mega</option>
                        <option value="300mb">⚡ 300 Mega</option>
                        <option value="500mb">💎 500 Mega</option>
                    </select>
                </div>
                
                <button type="submit" class="submit-btn" id="submitBtn">
                    🎉 CONFIRMAR E GIRAR 🎉
                </button>
            </form>
        </div>
    </div>

    <!-- Result Modal - Win -->
    <div class="modal result-modal" id="resultModal">
        <div class="modal-content">
            <div class="modal-icon" id="prizeIcon">🎊</div>
            <h2 id="prizeTitle">Viva o Carnaval!</h2>
            <div class="prize-display" id="prizeText"></div>
            <p id="prizeDescription"></p>
            <button class="submit-btn" onclick="closeResultModal()">
                🎭 RESGATAR PRÊMIO 📱
            </button>
        </div>
    </div>

    <!-- Result Modal - Lose -->
    <div class="modal result-modal lose" id="loseModal">
        <div class="modal-content">
            <div class="modal-icon">😢</div>
            <h2>Não foi dessa vez!</h2>
            <div class="prize-display">NÃO FOI<br>DESSA VEZ</div>
            <p>Mas não fique triste! O carnaval continua e temos planos especiais para você!</p>
            <button class="submit-btn" onclick="closeLoseModal()">
                🎪 VER PLANOS 📱
            </button>
            <button class="submit-btn try-again-btn" onclick="tryAgain()" style="margin-top: 10px;">
                🔄 TENTAR NOVAMENTE
            </button>
        </div>
    </div>

    <!-- Result Modal - Spin Again -->
    <div class="modal result-modal special" id="spinAgainModal">
        <div class="modal-content">
            <div class="modal-icon">🎉</div>
            <h2>Chance Extra!</h2>
            <div class="prize-display">GIRE<br>NOVAMENTE</div>
            <p>A folia não para! Você ganhou mais uma rodada na roleta!</p>
            <button class="submit-btn" onclick="spinAgain()" style="background: linear-gradient(135deg, #9400D3, #FF1493); color: white;">
                🎰 GIRAR NOVAMENTE 🎰
            </button>
        </div>
    </div>

    <!-- Social Buttons -->
    <div class="social-buttons">
        <a href="https://wa.me/5585921633795" target="_blank" class="social-btn whatsapp-btn" title="Fale conosco no WhatsApp">
            💬
        </a>
        <a href="https://instagram.com/sas_telecom_oficial" target="_blank" class="social-btn instagram-btn" title="Siga-nos no Instagram">
            📷
        </a>
    </div>

    <script>
        const CONFIG = {
            whatsappNumber: '5585921633795',
            emailTo: 'contato@sastelecom.com.br'
        };

        document.getElementById('telefone').addEventListener('input', function(e) {
            let value = e.target.value.replace(/\D/g, '');
            if (value.length > 11) value = value.slice(0, 11);
            
            if (value.length > 7) {
                value = `(${value.slice(0, 2)}) ${value.slice(2, 7)}-${value.slice(7)}`;
            } else if (value.length > 2) {
                value = `(${value.slice(0, 2)}) ${value.slice(2)}`;
            } else if (value.length > 0) {
                value = `(${value}`;
            }
            
            e.target.value = value;
        });

        let currentRotation = 0;
        let isSpinning = false;
        let userData = {};
        let canSpinAgain = false;

        const prizes = [
            { icon: '🎁', title: 'AXÉ! 🎉', text: '1 MÊS DE INTERNET GRÁTIS', desc: 'Você ganhou 1 mês de internet 100% gratuita! Viva o carnaval!', type: 'win' },
            { icon: '😢', title: 'Que pena!', text: 'NÃO FOI DESSA VEZ', desc: 'Mas não desanime! O carnaval continua!', type: 'lose' },
            { icon: '💚', title: 'SUPER OFERTA! 🎭', text: 'PRIMEIRO MÊS POR R$5', desc: 'Você ganhou o primeiro mês por apenas R$5,00!', type: 'win' },
            { icon: '😢', title: 'Que pena!', text: 'NÃO FOI DESSA VEZ', desc: 'Mas não desanime! O carnaval continua!', type: 'lose' },
            { icon: '🏷️', title: 'INCRÍVEL! 🎊', text: '3 MESES COM 50% OFF', desc: 'Você ganhou 50% de desconto nas 3 primeiras mensalidades!', type: 'win' },
            { icon: '😢', title: 'Que pena!', text: 'NÃO FOI DESSA VEZ', desc: 'Mas não desanime! O carnaval continua!', type: 'lose' },
            { icon: '🔄', title: 'CHANCE EXTRA! 🎪', text: 'GIRE NOVAMENTE', desc: 'Você ganhou mais uma rodada na roleta carnavalesca!', type: 'spinAgain' },
            { icon: '😢', title: 'Que pena!', text: 'NÃO FOI DESSA VEZ', desc: 'Mas não desanime! O carnaval continua!', type: 'lose' }
        ];

        function openModal() {
            if (isSpinning) return;
            document.getElementById('registerModal').style.display = 'flex';
        }

        function closeModal() {
            document.getElementById('registerModal').style.display = 'none';
        }

        function closeResultModal() {
            document.getElementById('resultModal').style.display = 'none';
            
            const prize = document.getElementById('prizeText').innerText;
            const message = `🎭 *CARNAVAL SAS TELECOM - NOVO GANHADOR!* 🎉

👤 *Nome:* ${userData.nome}
📱 *WhatsApp:* ${userData.telefone}
📍 *Endereço:* ${userData.endereco}
📡 *Plano escolhido:* ${userData.plano}

🏆 *PRÊMIO GANHO:* ${prize}

🎊 O cliente está aguardando contato para resgatar o prêmio de carnaval!`;

            window.open(`https://wa.me/${CONFIG.whatsappNumber}?text=${encodeURIComponent(message)}`, '_blank');
        }

        function closeLoseModal() {
            document.getElementById('loseModal').style.display = 'none';
            
            const message = `🎭 *CARNAVAL SAS TELECOM - NOVO LEAD* 🎉

👤 *Nome:* ${userData.nome}
📱 *WhatsApp:* ${userData.telefone}
📍 *Endereço:* ${userData.endereco}
📡 *Plano escolhido:* ${userData.plano}

😢 *Resultado:* Não ganhou na roleta, mas quer aproveitar o carnaval!

🎊 Entrar em contato com condições especiais de folia!`;

            window.open(`https://wa.me/${CONFIG.whatsappNumber}?text=${encodeURIComponent(message)}`, '_blank');
        }

        function tryAgain() {
            document.getElementById('loseModal').style.display = 'none';
            document.getElementById('registerForm').reset();
            openModal();
        }

        function spinAgain() {
            document.getElementById('spinAgainModal').style.display = 'none';
            canSpinAgain = true;
            document.getElementById('spinBtn').click();
        }

        async function saveData(data) {
            const leads = JSON.parse(localStorage.getItem('sasLeads') || '[]');
            leads.push({
                ...data,
                dataHora: new Date().toLocaleString('pt-BR'),
                userAgent: navigator.userAgent
            });
            localStorage.setItem('sasLeads', JSON.stringify(leads));

            try {
                await fetch(`https://formsubmit.co/ajax/${CONFIG.emailTo}`, {
                    method: 'POST',
                    headers: {
                        'Content-Type': 'application/json',
                        'Accept': 'application/json'
                    },
                    body: JSON.stringify({
                        nome: data.nome,
                        telefone: data.telefone,
                        endereco: data.endereco,
                        plano: data.plano,
                        data: new Date().toLocaleString('pt-BR'),
                        origem: 'Carnaval SAS TELECOM - Roleta'
                    })
                });
            } catch (e) {
                console.log('Erro ao enviar email:', e);
            }
        }

        async function startSpin(e) {
            e.preventDefault();
            
            const btn = document.getElementById('spinBtn');
            const submitBtn = document.getElementById('submitBtn');
            const wheel = document.getElementById('wheel');
            const successMsg = document.getElementById('successMessage');
            
            if (!canSpinAgain) {
                userData = {
                    nome: document.getElementById('nome').value,
                    telefone: document.getElementById('telefone').value,
                    endereco: document.getElementById('endereco').value,
                    plano: document.getElementById('plano').value
                };

                submitBtn.disabled = true;
                submitBtn.innerHTML = '<span class="loading"></span> SALVANDO...';
                
                await saveData(userData);
                
                successMsg.style.display = 'block';
                submitBtn.innerHTML = '✅ DADOS SALVOS!';
            }
            
            setTimeout(() => {
                closeModal();
                isSpinning = true;
                btn.disabled = true;
                btn.innerHTML = '<span class="loading"></span> SORTEANDO...';

                const prizeIndex = Math.floor(Math.random() * 8);
                
                const segmentAngle = 45;
                const targetAngle = 360 - (prizeIndex * segmentAngle) - 22.5;
                const spins = 5 * 360;
                const finalRotation = currentRotation + spins + targetAngle;
                
                wheel.style.transform = `rotate(${finalRotation}deg)`;
                currentRotation = finalRotation;

                setTimeout(() => {
                    showResult(prizeIndex);
                    isSpinning = false;
                    btn.disabled = false;
                    btn.innerHTML = '🎰 GIRAR ROLETA 🎰';
                    submitBtn.disabled = false;
                    submitBtn.innerHTML = '🎉 CONFIRMAR E GIRAR 🎉';
                    successMsg.style.display = 'none';
                    canSpinAgain = false;
                }, 5000);
            }, 1500);
        }

        function showResult(index) {
            const prize = prizes[index];
            
            if (prize.type === 'lose') {
                document.getElementById('loseModal').style.display = 'flex';
            } else if (prize.type === 'spinAgain') {
                document.getElementById('spinAgainModal').style.display = 'flex';
            } else {
                document.getElementById('prizeIcon').innerText = prize.icon;
                document.getElementById('prizeTitle').innerText = prize.title;
                document.getElementById('prizeText').innerText = prize.text;
                document.getElementById('prizeDescription').innerText = prize.desc;
                document.getElementById('resultModal').style.display = 'flex';
            }
        }

        window.onclick = function(event) {
            if (event.target.classList.contains('modal')) {
                event.target.style.display = 'none';
            }
        }
    </script>
</body>
</html>
