# DND-Backgrounds
<html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Official DND Backgrounds</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        .background-card {
            transition: all 0.3s ease;
        }
        .background-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.2);
        }
        .nav-link {
            position: relative;
        }
        .nav-link::after {
            content: '';
            position: absolute;
            width: 0;
            height: 2px;
            bottom: 0;
            left: 0;
            background-color: #d1a054;
            transition: width 0.3s ease;
        }
        .nav-link:hover::after {
            width: 100%;
        }
        .dice-roll {
            animation: roll 0.5s ease-out;
        }
        @keyframes roll {
            0% { transform: rotate(0deg); }
            25% { transform: rotate(90deg); }
            50% { transform: rotate(180deg); }
            75% { transform: rotate(270deg); }
            100% { transform: rotate(360deg); }
        }
    </style>
</head>
<body class="bg-gray-900 text-gray-100 font-sans">
    <!-- Header -->
    <header class="bg-gray-800 shadow-lg">
        <div class="container mx-auto px-4 py-6">
            <div class="flex flex-col md:flex-row justify-between items-center">
                <div class="flex items-center mb-4 md:mb-0">
                    <img src="https://dnd-backgrounds.my.canva.site/images/42d95f56d58f93b237487949250f7d58.svg" alt="DND Logo" class="h-16 w-16 mr-4">
                    <h1 class="text-3xl font-bold text-amber-500">DND Backgrounds</h1>
                </div>
                <nav class="flex space-x-6">
                    <a href="#" class="nav-link text-lg hover:text-amber-400">Home</a>
                    <a href="#backgrounds" class="nav-link text-lg hover:text-amber-400">Backgrounds</a>
                    <a href="#features" class="nav-link text-lg hover:text-amber-400">Features</a>
                    <a href="#contact" class="nav-link text-lg hover:text-amber-400">Contact</a>
                </nav>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="bg-gradient-to-b from-gray-800 to-gray-900 py-20">
        <div class="container mx-auto px-4 text-center">
            <h2 class="text-4xl md:text-6xl font-bold mb-6 text-amber-400">DND Backgrounds</h2>
            <p class="text-xl md:text-2xl mb-10 max-w-3xl mx-auto">And everything you need to know!</p>
            <img src="https://dnd-backgrounds.my.canva.site/images/6a8c8ecb60e8d3bdc5fc1283bdfba303.png" alt="DND Divider nigger" class="mx-auto mb-5 h-8">
            <a href="#backgrounds" class="bg-amber-600 hover:bg-amber-700 text-white font-bold py-3 px-8 rounded-full text-lg transition duration-300 inline-block">
                Explore Backgrounds
            </a>
        </div>
    </section>

    <!-- Main Backgrounds Section -->
    <section id="backgrounds" class="py-16 bg-gray-800">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold mb-12 text-center text-amber-400">Main Backgrounds</h2>
            
            <!-- Background Cards Grid -->
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Soldier Card -->
                <div class="background-card bg-gray-700 rounded-lg overflow-hidden shadow-lg">
                    <div class="bg-gray-600 p-4">
                        <h3 class="text-2xl font-bold text-amber-400">Soldier</h3>
                    </div>
                    <div class="p-6">
                        <ul class="space-y-3">
                            <li class="flex items-start">
                                <i class="fas fa-shield-alt text-amber-500 mt-1 mr-3"></i>
                                <span>Proficient in Athletics and Intimidation skills</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fas fa-helmet-battle text-amber-500 mt-1 mr-3"></i>
                                <span>Starting equipment includes chain mail, a shield, a military rank insignia</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fas fa-dice-d20 text-amber-500 mt-1 mr-3"></i>
                                <span>Set of bone dice or deck of cards, and a pouch containing 10 gp</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fas fa-medal text-amber-500 mt-1 mr-3"></i>
                                <span>Feature: Military Rank</span>
                            </li>
                        </ul>
                    </div>
                </div>

                <!-- Entertainer Card -->
                <div class="background-card bg-gray-700 rounded-lg overflow-hidden shadow-lg">
                    <div class="bg-gray-600 p-4">
                        <h3 class="text-2xl font-bold text-amber-400">Entertainer</h3>
                    </div>
                    <div class="p-6">
                        <ul class="space-y-3">
                            <li class="flex items-start">
                                <i class="fas fa-acrobatics text-amber-500 mt-1 mr-3"></i>
                                <span>Proficiencies: Acrobatics, Performance</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fas fa-music text-amber-500 mt-1 mr-3"></i>
                                <span>Tool Proficiencies: One type of musical instrument</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fas fa-guitar text-amber-500 mt-1 mr-3"></i>
                                <span>Equipment: A musical instrument (one of your choice)</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fas fa-heart text-amber-500 mt-1 mr-3"></i>
                                <span>The favor of an admirer (love letter, lock of hair, or trinket)</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fas fa-coins text-amber-500 mt-1 mr-3"></i>
                                <span>A costume, and a pouch containing 15 gp</span>
                            </li>
                        </ul>
                    </div>
                </div>

                <!-- Warlord Commander Card -->
                <div class="background-card bg-gray-700 rounded-lg overflow-hidden shadow-lg">
                    <div class="bg-gray-600 p-4">
                        <h3 class="text-2xl font-bold text-amber-400">Warlord Commander</h3>
                    </div>
                    <div class="p-6">
                        <ul class="space-y-3">
                            <li class="flex items-start">
                                <i class="fas fa-brain text-amber-500 mt-1 mr-3"></i>
                                <span>Skill Proficiencies: Athletics, Persuasion</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fas fa-language text-amber-500 mt-1 mr-3"></i>
                                <span>Languages: 2 of your choice</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fas fa-chess text-amber-500 mt-1 mr-3"></i>
                                <span>Tool Proficiencies: One type of gaming set</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fas fa-tshirt text-amber-500 mt-1 mr-3"></i>
                                <span>Equipment: A set of fine clothes, a gaming set of your choice</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fas fa-lightbulb text-amber-500 mt-1 mr-3"></i>
                                <span>Feature: Tactical Insight - Give advantage on Initiative rolls</span>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Featured Background Section -->
    <section class="py-16 bg-gray-900">
        <div class="container mx-auto px-4">
            <div class="flex flex-col lg:flex-row items-center">
                <div class="lg:w-1/2 mb-8 lg:mb-0 lg:pr-8">
                    <img src="https://dnd-backgrounds.my.canva.site/images/fce1f8ce8d6f9156325fe2b2239d876e.jpg" alt="Entertainer" class="rounded-lg shadow-xl w-full">
                </div>
                <div class="lg:w-1/2">
                    <h2 class="text-3xl font-bold mb-6 text-amber-400">Criminal Background</h2>
                    <ul class="space-y-4 text-lg">
                        <li class="flex items-start">
                            <i class="fas fa-mask text-amber-500 mt-1 mr-3"></i>
                            <span>Skill Proficiencies: Deception, Stealth</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fas fa-tools text-amber-500 mt-1 mr-3"></i>
                            <span>Tool Proficiencies: One type of gaming set, thieves' tools</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fas fa-language text-amber-500 mt-1 mr-3"></i>
                            <span>Languages: None</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fas fa-crowbar text-amber-500 mt-1 mr-3"></i>
                            <span>Equipment: A crowbar, a set of dark common clothes including a hood</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fas fa-money-bill-wave text-amber-500 mt-1 mr-3"></i>
                            <span>Pouch containing 15 gp</span>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- More Backgrounds Section -->
    <section id="features" class="py-16 bg-gray-800">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold mb-12 text-center text-amber-400">More Unique Backgrounds</h2>
            
            <!-- Tabs Navigation -->
            <div class="flex overflow-x-auto pb-2 mb-8 scrollbar-hide">
                <button onclick="showTab('addict')" class="tab-button px-6 py-3 font-medium rounded-t-lg bg-gray-700 text-amber-400 border-b-2 border-amber-400">
                    Addict
                </button>
                <button onclick="showTab('arena')" class="tab-button px-6 py-3 font-medium rounded-t-lg bg-gray-600 hover:bg-gray-700 text-gray-300 hover:text-amber-400">
                    Born to the Arena
                </button>
                <button onclick="showTab('progenitor')" class="tab-button px-6 py-3 font-medium rounded-t-lg bg-gray-600 hover:bg-gray-700 text-gray-300 hover:text-amber-400">
                    Progenitor
                </button>
                <button onclick="showTab('madman')" class="tab-button px-6 py-3 font-medium rounded-t-lg bg-gray-600 hover:bg-gray-700 text-gray-300 hover:text-amber-400">
                    Madman
                </button>
                <button onclick="showTab('bro')" class="tab-button px-6 py-3 font-medium rounded-t-lg bg-gray-600 hover:bg-gray-700 text-gray-300 hover:text-amber-400">
                    Absolute Bro
                </button>
                <button onclick="showTab('chosen')" class="tab-button px-6 py-3 font-medium rounded-t-lg bg-gray-600 hover:bg-gray-700 text-gray-300 hover:text-amber-400">
                    Almost the Chosen One
                </button>
            </div>
                            <!-- Add this right after the last tab button -->
                <button onclick="showTab('warcriminal')" class="tab-button px-6 py-3 font-medium rounded-t-lg bg-gray-600 hover:bg-gray-700 text-gray-300 hover:text-amber-400">
                    War Criminal
                </button>
            <!-- Tab Content -->
            <div id="addict" class="tab-content bg-gray-700 rounded-b-lg rounded-tr-lg p-6 shadow-lg">
                <div class="grid md:grid-cols-2 gap-8">
                    <div>
                        <h3 class="text-2xl font-bold mb-4 text-amber-400">Addict</h3>
                        <h4 class="text-xl font-semibold mb-2">Proficiencies:</h4>
                        <ul class="space-y-2 mb-6">
                            <li class="flex items-start">
                                <i class="fas fa-pills text-amber-500 mt-1 mr-3"></i>
                                <span>Skills: Deception or Persuasion (choose one), and proficiency in a skill related to your addiction</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fas fa-flask text-amber-500 mt-1 mr-3"></i>
                                <span>Tool: 1 set of tools related to facilitating your addiction</span>
                            </li>
                        </ul>
                        
                        <h4 class="text-xl font-semibold mb-2">Equipment:</h4>
                        <ul class="space-y-2 mb-6">
                            <li class="flex items-start">
                                <i class="fas fa-file-medical text-amber-500 mt-1 mr-3"></i>
                                <span>Medical diagnosis papers</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fas fa-syringe text-amber-500 mt-1 mr-3"></i>
                                <span>Paraphernalia related to your addiction</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fas fa-coins text-amber-500 mt-1 mr-3"></i>
                                <span>Common clothes, pouch containing 5gp</span>
                            </li>
                        </ul>
                    </div>
                    <div>
                        <h4 class="text-xl font-semibold mb-2">Feature: Strong Highs & Lows</h4>
                        <p class="mb-4">When you feed your addiction, you gain a strong high, granting you +1 on saves and checks with which you are proficient.</p>
                        <p class="mb-6">If you don't feed your addiction, you suffer withdrawal, resulting in -1 on ALL checks and saves.</p>
                        
                        <h4 class="text-xl font-semibold mb-2">ALT Feature: Enabled</h4>
                        <p class="mb-6">You have an enabler that feeds your addiction, ensuring stability.</p>
                        
                        <h4 class="text-xl font-semibold mb-2">ALT Feature: Recovering Addict</h4>
                        <p>You have seen the error of your ways and are trying to quit. When in the presence of your addiction, you must make a save to resist based on what the addiction is and make the save with disadvantage.</p>
                    </div>
                </div>
            </div>
            
            <div id="arena" class="tab-content hidden bg-gray-700 rounded-b-lg rounded-tr-lg p-6 shadow-lg">
                <div class="grid md:grid-cols-2 gap-8">
                    <div>
                        <h3 class="text-2xl font-bold mb-4 text-amber-400">Born to the Arena</h3>
                        <p class="mb-6 italic">Raised as a slave in the brutal arena, you've survived through cunning and strength. Now free, you embark on a new life, armed with skill and determination.</p>
                        
                        <h4 class="text-xl font-semibold mb-2">Proficiencies:</h4>
                        <ul class="space-y-2 mb-6">
                            <li class="flex items-start">
                                <i class="fas fa-fist-raised text-amber-500 mt-1 mr-3"></i>
                                <span>Skill Proficiencies: Survival, Acrobatics</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fas fa-tools text-amber-500 mt-1 mr-3"></i>
                                <span>Tool Proficiencies: Leatherworker's tools, Smith's tools</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fas fa-language text-amber-500 mt-1 mr-3"></i>
                                <span>Languages: Common, plus one additional language learned through necessity</span>
                            </li>
                        </ul>
                        
                        <h4 class="text-xl font-semibold mb-2">Equipment:</h4>
                        <ul class="space-y-2">
                            <li class="flex items-start">
                                <i class="fas fa-sword text-amber-500 mt-1 mr-3"></i>
                                <span>Exotic weapon, token of family, arena leathers</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fas fa-coins text-amber-500 mt-1 mr-3"></i>
                                <span>Pouch containing 10 gp</span>
                            </li>
                        </ul>
                    </div>
                    <div>
                        <h4 class="text-xl font-semibold mb-2">Feature: Master of Weapons</h4>
                        <p class="mb-6">Having fought with a variety of weapons in the arena, you are proficient with both simple and martial weapons and can become proficient with a new exotic weapon given time.</p>
                        
                        <div class="bg-gray-600 p-4 rounded-lg mb-6">
                            <h4 class="text-lg font-semibold mb-2 text-amber-400">Suggested Characteristics</h4>
                            <p>Arena slaves live lives filled hardships and pain, both physical and psychological. These souls are driven and survivors by necessity. They often form strong familial bonds with their fighting partners and fellow slaves, and share a burning desire for a better life, a life of freedom.</p>
                        </div>
                        
                        <button onclick="rollDice('arena-dice')" class="bg-amber-600 hover:bg-amber-700 text-white font-bold py-2 px-4 rounded mb-4">
                            Roll for Traits <i class="fas fa-dice-d20 ml-2"></i>
                        </button>
                        <div id="arena-dice" class="bg-gray-600 p-4 rounded-lg"></div>
                    </div>
                </div>
            </div>
            
            <div id="progenitor" class="tab-content hidden bg-gray-700 rounded-b-lg rounded-tr-lg p-6 shadow-lg">
                <div class="grid md:grid-cols-2 gap-8">
                    <div>
                        <h3 class="text-2xl font-bold mb-4 text-amber-400">Progenitor</h3>
                        <p class="mb-6">Originating from a lineage of prolific progenitors, your character possesses unique traits inherited from their ancestors. This background delves into your character's heritage, fertility, and persuasive abilities.</p>
                        
                        <h4 class="text-xl font-semibold mb-2">Proficiencies:</h4>
                        <ul class="space-y-2 mb-6">
                            <li class="flex items-start">
                                <i class="fas fa-comments text-amber-500 mt-1 mr-3"></i>
                                <span>Skill Proficiencies: Persuasion, Performance</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fas fa-language text-amber-500 mt-1 mr-3"></i>
                                <span>Languages: Common and one additional language of your choice</span>
                            </li>
                        </ul>
                        
                        <h4 class="text-xl font-semibold mb-2">Equipment:</h4>
                        <ul class="space-y-2 mb-6">
                            <li class="flex items-start">
                                <i class="fas fa-ring text-amber-500 mt-1 mr-3"></i>
                                <span>A symbol or token of your familial heritage</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fas fa-tshirt text-amber-500 mt-1 mr-3"></i>
                                <span>A set of fine clothes</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fas fa-coins text-amber-500 mt-1 mr-3"></i>
                                <span>A pouch containing 15 gold pieces</span>
                            </li>
                        </ul>
                    </div>
                    <div>
                        <div class="bg-gray-600 p-4 rounded-lg mb-6">
                            <h4 class="text-lg font-semibold mb-2 text-amber-400">Suggested Characteristics</h4>
                            <p>Personality Traits, Ideals, Bonds, and Flaws that define your progenitor character.</p>
                        </div>
                        
                        <button onclick="rollDice('progenitor-dice')" class="bg-amber-600 hover:bg-amber-700 text-white font-bold py-2 px-4 rounded mb-4">
                            Roll for Traits <i class="fas fa-dice-d20 ml-2"></i>
                        </button>
                        <div id="progenitor-dice" class="bg-gray-600 p-4 rounded-lg"></div>
                    </div>
                </div>
            </div>
            
            <div id="madman" class="tab-content hidden bg-gray-700 rounded-b-lg rounded-tr-lg p-6 shadow-lg">
                <div class="grid md:grid-cols-2 gap-8">
                    <div>
                        <h3 class="text-2xl font-bold mb-4 text-amber-400">Madman</h3>
                        <p class="mb-6 italic">Your sanity left you long ago. Perhaps you spent a few too many moments on another plane or contacted one of the Great Old Ones; possibly you suffered a traumatic event and your mind simply caved under the stress.</p>
                        
                        <h4 class="text-xl font-semibold mb-2">Proficiencies:</h4>
                        <ul class="space-y-2 mb-6">
                            <li class="flex items-start">
                                <i class="fas fa-brain text-amber-500 mt-1 mr-3"></i>
                                <span>Choose two of Perception, Deception, Intimidation, Persuasion</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fas fa-language text-amber-500 mt-1 mr-3"></i>
                                <span>Languages: Choose two exotic languages</span>
                            </li>
                        </ul>
                        
                        <h4 class="text-xl font-semibold mb-2">Equipment:</h4>
                        <ul class="space-y-2">
                            <li class="flex items-start">
                                <i class="fas fa-backpack text-amber-500 mt-1 mr-3"></i>
                                <span>An Entertainer's pack and one trinket</span>
                            </li>
                        </ul>
                    </div>
                    <div>
                        <h4 class="text-xl font-semibold mb-2">Feature: Shattered Mind</h4>
                        <p class="mb-6">Those who look into your eyes can see nothing beyond them. Though they might try, no one can divine your thoughts or intentions. Any creature that attempts to read your mind must succeed on a wisdom saving throw or be plunged into madness.</p>
                        
                        <div class="bg-gray-600 p-4 rounded-lg mb-6">
                            <h4 class="text-lg font-semibold mb-2 text-amber-400">Madness Table</h4>
                            <p>Choose a manifestation of your madness or roll for one:</p>
                            <ol class="list-decimal pl-5 mt-2">
                                <li>Paranoia - Everything is hell bent on your destruction</li>
                                <li>Mania - Your understanding is deranged and reasoning is absent</li>
                                <li>Incoherence - Your emotions are mismatched and you forget things</li>
                                <li>Split Personality - You aren't the only tenant of your body</li>
                            </ol>
                        </div>
                    </div>
                </div>
            </div>
            
            <div id="bro" class="tab-content hidden bg-gray-700 rounded-b-lg rounded-tr-lg p-6 shadow-lg">
                <div class="grid md:grid-cols-2 gap-8">
                    <div>
                        <h3 class="text-2xl font-bold mb-4 text-amber-400">Absolute Bro</h3>
                        <p class="mb-6">You put comradery and friendship above all else in your life. Your bros can always count on you to help when they are in a pinch, and you always go out out of your way to help those in need.</p>
                        
                        <h4 class="text-xl font-semibold mb-2">Proficiencies:</h4>
                        <ul class="space-y-2 mb-6">
                            <li class="flex items-start">
                                <i class="fas fa-paw text-amber-500 mt-1 mr-3"></i>
                                <span>Choose two from Animal Handling, Survival, Performance, and Persuasion</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fas fa-tools text-amber-500 mt-1 mr-3"></i>
                                <span>Tool Proficiencies: One type of artisan's tools, and either vehicles (land) or Brewer's Supplies</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fas fa-language text-amber-500 mt-1 mr-3"></i>
                                <span>Languages: Common, and one other language of your choice</span>
                            </li>
                        </ul>
                    </div>
                    <div>
                        <h4 class="text-xl font-semibold mb-2">Equipment:</h4>
                        <ul class="space-y-2 mb-6">
                            <li class="flex items-start">
                                <i class="fas fa-tools text-amber-500 mt-1 mr-3"></i>
                                <span>A set of artisan's tools (one of your choice)</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fas fa-tshirt text-amber-500 mt-1 mr-3"></i>
                                <span>A set of fine clothes</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fas fa-coins text-amber-500 mt-1 mr-3"></i>
                                <span>A pouch containing 5 gp</span>
                            </li>
                        </ul>
                        
                        <h4 class="text-xl font-semibold mb-2">Feature: Life of the Party</h4>
                        <p class="mb-6">You have a knack for finding the party in any establishment, and people tend to gravitate toward your presence when you are having a good time. You can easily find the location of any social gathering, and you have advantage on Charisma checks to gain entrance to special event without an invitation.</p>
                    </div>
                </div>
            </div>
            
            <div id="chosen" class="tab-content hidden bg-gray-700 rounded-b-lg rounded-tr-lg p-6 shadow-lg">
                <div class="grid md:grid-cols-2 gap-8">
                    <div>
                        <h3 class="text-2xl font-bold mb-4 text-amber-400">Almost the Chosen One</h3>
                        <p class="mb-6">Thousands of years ago a prophecy in your kingdom foretold of a great evil rising to power and of a great good that would vanquish that evil. It was said that that person would be born under the right combination of stars, with the right hair color, the right eye color, and a birthmark in one specific place. Sadly your older twin is the one with the birthmark, not you.</p>
                        
                        <h4 class="text-xl font-semibold mb-2">Proficiencies:</h4>
                        <ul class="space-y-2 mb-6">
                            <li class="flex items-start">
                                <i class="fas fa-eye-slash text-amber-500 mt-1 mr-3"></i>
                                <span>Stealth (no one is looking anyway)</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fas fa-theater-masks text-amber-500 mt-1 mr-3"></i>
                                <span>Deception</span>
                            </li>
                        </ul>
                        
                        <h4 class="text-xl font-semibold mb-2">Equipment:</h4>
                        <ul class="space-y-2">
                            <li class="flex items-start">
                                <i class="fas fa-tshirt text-amber-500 mt-1 mr-3"></i>
                                <span>Common Clothes; 1 days rations; 1 water skin</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fas fa-tools text-amber-500 mt-1 mr-3"></i>
                                <span>Disguise Kit, Forgery Kit, or Thieves' Tools depending on proficiencies</span>
                            </li>
                        </ul>
                    </div>
                    <div>
                        <h4 class="text-xl font-semibold mb-2">Feature: Sibling of the Chosen One</h4>
                        <p class="mb-6">Due to the status of your sibling, people don't look in your direction if your sibling is near. Everyone is too awestruck by your sibling, and don't give two flying chamber pots about you. However, you can get certain things for free, like whatever you can get your hands on while no one is looking.</p>
                        
                        <button onclick="rollDice('chosen-dice')" class="bg-amber-600 hover:bg-amber-700 text-white font-bold py-2 px-4 rounded mb-4">
                            Roll for Traits <i class="fas fa-dice-d20 ml-2"></i>       
                        </button>
                        <div id="chosen-dice" class="bg-gray-600 p-4 rounded-lg"></div>
                      <div id="warcriminal" class="tab-content hidden bg-gray-700 rounded-b-lg rounded-tr-lg p-6 shadow-lg">
    <div class="grid md:grid-cols-2 gap-8">
        <div>
            <h3 class="text-2xl font-bold mb-4 text-amber-400">War Criminal</h3>
            <p class="mb-6 italic">You betrayed your kingdom or army through unethical tactics, treasonous acts, or war crimes. Now you're either on the run or facing the consequences of your actions.</p>
          <h4 class="text-xl font-semibold mb-2">Proficiencies:</h4>
            <ul class="space-y-2 mb-6">
                <li class="flex items-start">
                    <i class="fas fa-brain text-amber-500 mt-1 mr-3"></i>
                    <span>Skills: Deception, History (Athletics if Soldier, Perception if Noble)</span>
                </li>
                <li class="flex items-start">
                    <i class="fas fa-tools text-amber-500 mt-1 mr-3"></i>
                    <span>Tools: Poisoner's Kit or Disguise Kit + Gaming Set</span>
                </li>
            </ul>
            
            <h4 class="text-xl font-semibold mb-2">Equipment:</h4>
            <ul class="space-y-2 mb-6">
                <li class="flex items-start">
                    <i class="fas fa-tshirt text-amber-500 mt-1 mr-3"></i>
                    <span>Dark common clothes with hood</span>
                </li>
                <li class="flex items-start">
                    <i class="fas fa-trophy text-amber-500 mt-1 mr-3"></i>
                    <span>Trophy from a noble/general you killed</span>
                </li>
                <li class="flex items-start">
                    <i class="fas fa-ring text-amber-500 mt-1 mr-3"></i>
                    <span>Signet ring (if noble) or dice/cards (if soldier)</span>
                </li>
                <li class="flex items-start">
                    <i class="fas fa-coins text-amber-500 mt-1 mr-3"></i>
                    <span>10 gp</span>
                </li>
            </ul>
            
            <h4 class="text-xl font-semibold mb-2">War Crimes:</h4>
            <div class="overflow-x-auto">
                <table class="w-full bg-gray-600 rounded-lg">
                    <thead>
                        <tr class="bg-gray-500">
                            <th class="px-4 py-2 text-left">d10</th>
                            <th class="px-4 py-2 text-left">Act of Treason</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr><td class="px-4 py-2">1</td><td class="px-4 py-2">Gave sensitive information to the enemy</td></tr>
                        <tr class="bg-gray-600"><td class="px-4 py-2">2</td><td class="px-4 py-2">Staged a coup d'etat against nobility</td></tr>
                        <tr><td class="px-4 py-2">3</td><td class="px-4 py-2">Coated weapons in poison for combat</td></tr>
                        <tr class="bg-gray-600"><td class="px-4 py-2">4</td><td class="px-4 py-2">Let prisoners escape</td></tr>
                        <tr><td class="px-4 py-2">5</td><td class="px-4 py-2">Killed officer/general for self-interest</td></tr>
                        <tr class="bg-gray-600"><td class="px-4 py-2">6</td><td class="px-4 py-2">Deserted at crucial hour</td></tr>
                        <tr><td class="px-4 py-2">7</td><td class="px-4 py-2">Staged fake peace talks to slaughter nobility</td></tr>
                        <tr class="bg-gray-600"><td class="px-4 py-2">8</td><td class="px-4 py-2">Murdered the king</td></tr>
                        <tr><td class="px-4 py-2">9</td><td class="px-4 py-2">Made false declaration of war</td></tr>
                        <tr class="bg-gray-600"><td class="px-4 py-2">10</td><td class="px-4 py-2">Revealed marching schedule for ambush</td></tr>
                    </tbody>
                </table>
            </div>
        </div>
        
        <div>
            <h4 class="text-xl font-semibold mb-2">Feature: Bounty</h4>
            <p class="mb-4">Your country has placed a sizable bounty on your head. You must stay vigilant and maintain a false identity.</p>
            
            <h4 class="text-xl font-semibold mb-2 mt-6">ALT Feature: Treacherous Debt</h4>
            <p class="mb-6">The country you conspired with owes you refuge, but their hospitality may come with conditions.</p>
            
            <h4 class="text-xl font-semibold mb-2">Suggested Characteristics</h4>
            <div class="bg-gray-600 p-4 rounded-lg mb-4">
                <h5 class="font-semibold text-amber-400 mb-2">Personality Traits (d8)</h5>
                <ol class="list-decimal pl-5 space-y-1">
                    <li>Nothing I won't do for profit</li>
                    <li>Daily doubts about my actions</li>
                    <li>Pleasure in others' suffering</li>
                    <li>Seeking atonement through helping</li>
                    <li>Righting wrongs at any cost</li>
                    <li>Poor judgment, impulsive</li>
                    <li>Act only out of self-interest</li>
                    <li>Value loved ones over homeland</li>
                </ol>
            </div>
            
            <div class="bg-gray-600 p-4 rounded-lg mb-4">
                <h5 class="font-semibold text-amber-400 mb-2">Ideals (d6)</h5>
                <ol class="list-decimal pl-5 space-y-1">
                    <li>Duty: A man's gotta do...</li>
                    <li>Sides: Fight for what's right</li>
                    <li>Karma: I'll get what's coming</li>
                    <li>Anarchy: Meaningless without conflict</li>
                    <li>Spite: Governments will burn</li>
                    <li>Change: Complacency is death</li>
                </ol>
            </div>
            
            <div class="bg-gray-600 p-4 rounded-lg mb-4">
                <h5 class="font-semibold text-amber-400 mb-2">Bonds (d6)</h5>
                <ol class="list-decimal pl-5 space-y-1">
                    <li>Right those I've wronged</li>
                    <li>Seek redemption</li>
                    <li>Prevent loved ones' deaths</li>
                    <li>Finish what I started</li>
                    <li>Kill my blackmailer</li>
                    <li>Loyal to new country</li>
                </ol>
            </div>
            
            <div class="bg-gray-600 p-4 rounded-lg">
                <h5 class="font-semibold text-amber-400 mb-2">Flaws (d6)</h5>
                <ol class="list-decimal pl-5 space-y-1">
                    <li>Defend actions to the grave</li>
                    <li>Indifferent to innocent deaths</li>
                    <li>Paranoid about trust</li>
                    <li>Never share secrets</li>
                    <li>Sell out friends for safety</li>
                    <li>Chronic poor judgment</li>
                </ol>
            </div>
            
            <button onclick="rollDice('warcriminal-dice')" class="bg-amber-600 hover:bg-amber-700 text-white font-bold py-2 px-4 rounded mt-6">
                Roll Random Traits <i class="fas fa-dice-d20 ml-2"></i>
            </button>
            <div id="warcriminal-dice" class="bg-gray-600 p-4 rounded-lg mt-4"></div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer id="contact" class="bg-gray-900 py-12">
        <div class="container mx-auto px-4">
            <div class="flex flex-col md:flex-row justify-between">
                <div class="mb-8 md:mb-0">
                    <h3 class="text-2xl font-bold mb-4 text-amber-400">Official DND Backgrounds</h3>
                    <p class="mb-4">We're working hard to add more content...</p>
                    <div class="flex space-x-4">
                        <a href="#" class="text-gray-400 hover:text-amber-400 transition duration-300">
                            <i class="fab fa-instagram text-2xl"></i>
                        </a>
                        <a href="#" class="text-gray-400 hover:text-amber-400 transition duration-300">
                            <i class="fab fa-facebook text-2xl"></i>
                        </a>
                        <a href="#" class="text-gray-400 hover:text-amber-400 transition duration-300">
                            <i class="fab fa-twitter text-2xl"></i>
                        </a>
                        <a href="#" class="text-gray-400 hover:text-amber-400 transition duration-300">
                            <i class="fab fa-linkedin text-2xl"></i>
                        </a>
                    </div>
                </div>
                <div>
                    <h4 class="text-xl font-semibold mb-4 text-amber-400">Contact Us</h4>
                    <address class="not-italic">
                        <p class="mb-2">New York, New York</p>
                        <p class="mb-2">2911 Broadway</p>
                        <p class="mb-2">New York, 10025</p>
                        <p>212-439-1008</p>
                    </address>
                </div>
            </div>
            <div class="border-t border-gray-700 mt-8 pt-8 text-center text-gray-500">
                <p>&copy; 2025 Official DND Backgrounds. All rights reserved.</p>
            </div>
        </div>
    </footer>

    <script>
        // Show the first tab by default
        document.addEventListener('DOMContentLoaded', function() {
            showTab('addict');
        });

        function showTab(tabId) {
            // Hide all tab contents
            const tabContents = document.querySelectorAll('.tab-content');
            tabContents.forEach(content => {
                content.classList.add('hidden');
            });

            // Remove active class from all tab buttons
            const tabButtons = document.querySelectorAll('.tab-button');
            tabButtons.forEach(button => {
                button.classList.remove('bg-gray-700', 'text-amber-400', 'border-b-2', 'border-amber-400');
                button.classList.add('bg-gray-600', 'text-gray-300');
            });

            // Show the selected tab content
            document.getElementById(tabId).classList.remove('hidden');

            // Add active class to the clicked tab button
            const activeButton = document.querySelector(`button[onclick="showTab('${tabId}')"]`);
            activeButton.classList.remove('bg-gray-600', 'text-gray-300');
            activeButton.classList.add('bg-gray-700', 'text-amber-400', 'border-b-2', 'border-amber-400');
        }

        function rollDice(elementId) {
            const diceElement = document.getElementById(elementId);
            diceElement.innerHTML = '<div class="text-center"><i class="fas fa-dice-d20 text-4xl text-amber-500 dice-roll"></i></div>';
            
            setTimeout(() => {
                let content = '';
                
                if (elementId === 'arena-dice') {
                    const traits = [
                        "I need to always have a weapon near me, I always try to hide weapons somewhere in my person.",
                        "I'm always looking around for potential treats.",
                        "I like to sleep in smaller places, with my back to a wall, where no one else can sneak up on me.",
                        "I sleep with my back to a wall or tree, with everything I own wrapped in a bundle in my arms.",
                        "I eat like a pig and have bad manners.",
                        "I think anyone who's nice to me is hiding evil intent.",
                        "I don't like to bathe.",
                        "I bluntly say what other people are hinting at or hiding."
                    ];
                    
                    const ideals = [
                        "Respect. You don't deserve respect, you have to earn it.",
                        "Community. We have to take care of each other, because no one else is going to do it. (Lawful)",
                        "Change. The low are lifted up, and those in power will be brought down. Change is the nature of things. (Chaotic)",
                        "Retribution. Those in authority need to be shown what life and death are like in the gutters.",
                        "People. I help the people who help me — that's what keeps us alive. (Neutral)",
                        "Aspiration. I'm going to prove that I'm worthy of a better life."
                    ];
                    
                    const bonds = [
                        "My family or clan is my home, and I'll fight to defend it.",
                        "I try to sponsor other slaves to attain their freedom to keep others from enduring what I was forced to endure.",
                        "I owe my survival to another slave who taught me to live on the streets.",
                        "I owe a debt I can never repay to the person who took pity on me.",
                        "I escaped my life of poverty by robbing an important person, and I'm wanted for it.",
                        "No one else should have to endure the hardships I've been through."
                    ];
                    
                    const flaws = [
                        "I despise running away from a fight, even If I'm outnumbered.",
                        "Gold seems like a lot of money to me, and I'll do just about anything for more of it.",
                        "I will never fully trust anyone other than myself.",
                        "I'd rather kill someone in a one to one fight, A backstab is a cheap win.",
                        "It's not stealing if I need it more than someone else.",
                        "People who can't take care of themselves get what they deserve."
                    ];
                    
                    const randomTrait = traits[Math.floor(Math.random() * traits.length)];
                    const randomIdeal = ideals[Math.floor(Math.random() * ideals.length)];
                    const randomBond = bonds[Math.floor(Math.random() * bonds.length)];
                    const randomFlaw = flaws[Math.floor(Math.random() * flaws.length)];
                    
                    content = `
                        <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
                            <div>
                                <h5 class="font-semibold text-amber-400">Personality Trait</h5>
                                <p>${randomTrait}</p>
                            </div>
                            <div>
                                <h5 class="font-semibold text-amber-400">Ideal</h5>
                                <p>${randomIdeal}</p>
                            </div>
                            <div>
                                <h5 class="font-semibold text-amber-400">Bond</h5>
                                <p>${randomBond}</p>
                            </div>
                            <div>
                                <h5 class="font-semibold text-amber-400">Flaw</h5>
                                <p>${randomFlaw}</p>
                            </div>
                        </div>
                    `;
                } else if (elementId === 'progenitor-dice') {
                    const traits = [
                        "I'm a smooth talker, able to seduce even the most resistant partner with my charm. (Chaotic)",
                        "I'm always seeking out new opportunities for passion and pleasure, living life to the fullest. (Neutral)",
                        "Loyalty is important to me, and I'll do whatever it takes to protect and provide for my family. (Lawful)",
                        "I'm a hopeless romantic, believing in true love and happily ever afters. (Good)",
                        "I have a mischievous streak, enjoying the thrill of the chase and the excitement of forbidden romance. (Chaotic)",
                        "I'm fiercely competitive when it comes to matters of the heart, always striving to be the best lover in town. (Neutral)"
                    ];
                    
                    const ideals = [
                        "Love. I believe in the power of love to conquer all obstacles and bring happiness to those who seek it. (Good)",
                        "Freedom. I cherish the freedom to pursue my desires and live life on my own terms, without constraint. (Chaotic)",
                        "Legacy. I am driven to leave behind a legacy of love and passion, ensuring that my family line continues for generations to come. (Lawful)",
                        "Lust. I embrace my primal desires and revel in the pleasures of the flesh, indulging in every opportunity for intimacy. (Chaotic)",
                        "Connection. I value deep, meaningful connections with others, seeking out companionship and understanding in a world filled with fleeting encounters. (Neutral)",
                        "Romance. Life is a grand adventure, and I'm always on the lookout for my next great love story, ready to sweep someone off their feet. (Neutral)"
                    ];
                    
                    const bonds = [
                        "My family is my rock, and I'll do whatever it takes to protect and provide for them, even if it means making sacrifices of my own. (Lawful)",
                        "I'm on a quest to find my soulmate, the one who will complete me and share in the joys and sorrows of life. (Good)",
                        "I'm fiercely loyal to those I care about, willing to fight tooth and nail to defend their honor and protect their interests. (Lawful)",
                        "My heart belongs to someone special, and I'll stop at nothing to win their affections and build a future together. (Good)",
                        "I'm searching for the one who will ignite the flames of passion within me, the one who will make me feel alive like never before. (Chaotic)",
                        "My family's legacy is at stake, and I'm determined to ensure that our bloodline continues for generations to come, no matter the cost. (Neutral)"
                    ];
                    
                    const flaws = [
                        "My desire for romance sometimes leads me to make foolish decisions and take unnecessary risks, endangering myself and those around me. (Chaotic)",
                        "I can be possessive and jealous when it comes to matters of the heart (Neutral)",
                        "I'm a sucker for a pretty face (Chaotic)",
                        "I have a habit of falling too hard and too fast (Good?)",
                        "I'm so focused on finding love that I sometimes overlook the needs and desires of those closest to me, neglecting my responsibilities in the process. (Neutral)",
                        "I'm a hopeless romantic at heart. (Good)"
                    ];
                    
                    const randomTrait = traits[Math.floor(Math.random() * traits.length)];
                    const randomIdeal = ideals[Math.floor(Math.random() * ideals.length)];
                    const randomBond = bonds[Math.floor(Math.random() * bonds.length)];
                    const randomFlaw = flaws[Math.floor(Math.random() * flaws.length)];
                    
                    content = `
                        <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
                            <div>
                                <h5 class="font-semibold text-amber-400">Personality Trait</h5>
                                <p>${randomTrait}</p>
                            </div>
                            <div>
                                <h5 class="font-semibold text-amber-400">Ideal</h5>
                                <p>${randomIdeal}</p>
                            </div>
                            <div>
                                <h5 class="font-semibold text-amber-400">Bond</h5>
                                <p>${randomBond}</p>
                            </div>
                            <div>
                                <h5 class="font-semibold text-amber-400">Flaw</h5>
                                <p>${randomFlaw}</p>
                            </div>
                        </div>
                    `;
                } else if (elementId === 'chosen-dice') {
                    const traits = [
                        "I am persistent, even if I fail I will keep trying until I get it right.",
                        "I have to do something that no one has ever done before to prove my worth.",
                        "When people talk to me I assume they are talking to someone else and sometimes ignore them completely.",
                        "I often pretend to be my sibling.",
                        "I am prone to complaining uncontrollably about the smallest things.",
                        "I automatically assume that everyone is better at everything than me.",
                        "Having no self esteem, I will needlessly put myself in dangerous situations when I think it will protect someone else.",
                        "I don't know how to talk about anything other than my sibling."
                    ];
                    
                    const ideals = [
                        "Control: One day, I'll make the world see that prophecies are meaningless; I control my destiny. (Any)",
                        "Equality: Those in power, like my sibling, should not overlook those who are weaker, like myself. (Lawful)",
                        "Sidekick: I will help protect everyone to make things easier on my sibling. (Good)",
                        "Isolationism: I want to explore the world without living in my sibling's shadow. (Neutral)",
                        "Adventure: I will try everything at least once, since I haven't had the chance before. (Chaotic)",
                        "Villain: If I can destroy the world before my sibling saves it, I'll finally prove they're not so great. (Evil)"
                    ];
                    
                    const bonds = [
                        "I want to kill my sibling and take their place.",
                        "Only my god can be depended on.",
                        "I will be an asset to anyone willing to see me for me.",
                        "If I can't get people to like me, maybe I can get animals to like me.",
                        "I can't let my companions find out how uncool I actually am.",
                        "My parents have supported me more then anyone else, I will make them proud."
                    ];
                    
                    const flaws = [
                        "I will forgo sleep if it means training to be better then my sibling.",
                        "I actually think I am the chosen one and will act accordingly.",
                        "I can't stand people I think are better than me.",
                        "I will desperately pursue adventure if it means showing up my sibling.",
                        "I secretly have deep attractions and feelings for my sibling.",
                        "My anxiety from my sibling has lead to a massive drinking problem I can't kick.",
                        "I will accept any challenge if it makes me seem better then my sibling.",
                        "I'm cowardly and often find myself running from battles, screaming for someone's help."
                    ];
                    
                    const randomTrait = traits[Math.floor(Math.random() * traits.length)];
                    const randomIdeal = ideals[Math.floor(Math.random() * ideals.length)];
                    const randomBond = bonds[Math.floor(Math.random() * bonds.length)];
                    const randomFlaw = flaws[Math.floor(Math.random() * flaws.length)];
                    
                    content = `
                        <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
                            <div>
                                <h5 class="font-semibold text-amber-400">Personality Trait</h5>
                                <p>${randomTrait}</p>
                            </div>
                            <div>
                                <h5 class="font-semibold text-amber-400">Ideal</h5>
                                <p>${randomIdeal}</p>
                            </div>
                            <div>
                                <h5 class="font-semibold text-amber-400">Bond</h5>
                                <p>${randomBond}</p>
                            </div>
                            <div>
                                <h5 class="font-semibold text-amber-400">Flaw</h5>
                                <p>${randomFlaw}</p>
                            </div>
                        </div>
                    `;
                }
                
                diceElement.innerHTML = content;
            }, 500);
        }
    </script>
</body>
</html>
