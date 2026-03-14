<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=yes">
    <title>Коктейльное меню | FOROS</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Roboto, system-ui, -apple-system, sans-serif;
        }
        body {
            background: #faf9f7;
            padding: 20px 16px 40px;
            max-width: 600px;
            margin: 0 auto;
        }
        h1 {
            font-size: 2.2rem;
            font-weight: 600;
            letter-spacing: -0.02em;
            color: #1e1e1e;
            margin-bottom: 4px;
            padding-left: 8px;
        }
        .subhead {
            font-size: 1rem;
            color: #6b6b6b;
            margin-bottom: 32px;
            padding-left: 8px;
            border-left: 4px solid #c79b6e;
        }
        .category {
            margin-bottom: 40px;
        }
        .category-title {
            font-size: 1.6rem;
            font-weight: 500;
            color: #2c2c2c;
            margin-bottom: 16px;
            padding-bottom: 6px;
            border-bottom: 2px dashed #d4b595;
            display: flex;
            align-items: center;
            gap: 8px;
        }
        .category-title span {
            background: #e8d9cc;
            border-radius: 30px;
            padding: 4px 14px;
            font-size: 0.9rem;
            font-weight: 400;
            color: #4a3a2c;
        }
        .cocktail-grid {
            display: flex;
            flex-direction: column;
            gap: 16px;
        }
        .cocktail-card {
            display: flex;
            align-items: flex-start; /* выровняли по верхнему краю, чтобы текст не съезжал */
            background: white;
            border-radius: 24px;
            padding: 12px 16px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.04);
            transition: all 0.2s;
            border: 1px solid rgba(0,0,0,0.02);
        }
        .cocktail-card:active {
            transform: scale(0.99);
            background: #fefefe;
        }
        .cocktail-image {
            width: 70px;
            height: 70px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 2.4rem;
            margin-right: 18px;
            flex-shrink: 0;
            background: #f3ede8;
            color: #4f3f30;
            box-shadow: inset 0 -2px 0 rgba(0,0,0,0.05);
        }
        .category-milk .cocktail-image { background: #f9e5d2; }
        .category-non-alcohol .cocktail-image { background: #d7f0e6; }
        .category-alcohol .cocktail-image { background: #d9e5f5; }

        .cocktail-info {
            flex: 1;
        }
        .cocktail-info h3 {
            font-size: 1.2rem;
            font-weight: 600;
            margin-bottom: 6px;
            color: #1e1e1e;
            line-height: 1.3;
        }
        .ingredients {
            font-size: 0.85rem;
            color: #6f6f6f;
            margin-bottom: 10px;
            line-height: 1.4;
            /* убрали ограничение по высоте — теперь текст виден полностью */
            white-space: normal;
            overflow: visible;
        }
        .details {
            display: flex;
            justify-content: space-between;
            align-items: center;
            font-weight: 500;
        }
        .volume {
            background: #f0f0f0;
            padding: 4px 12px;
            border-radius: 40px;
            font-size: 0.8rem;
            color: #3d3d3d;
        }
        .price {
            font-size: 1.2rem;
            font-weight: 700;
            color: #b37b4c;
        }
        .price::after {
            content: " ₽";
            font-weight: 600;
            font-size: 0.95rem;
        }
        .footer-note {
            margin-top: 48px;
            text-align: center;
            color: #aaa;
            font-size: 0.8rem;
            border-top: 1px solid #e0e0e0;
            padding-top: 20px;
        }
    </style>
</head>
<body>
    <h1>🍸 FOROS</h1>
    <div class="subhead">коктейльная карта</div>

    <!-- Молочные коктейли -->
    <section class="category category-milk">
        <div class="category-title">🥛 Молочные коктейли <span>300 мл</span></div>
        <div class="cocktail-grid">
            <div class="cocktail-card">
                <div class="cocktail-image">🍦</div>
                <div class="cocktail-info">
                    <h3>Классический</h3>
                    <p class="ingredients">Пломбир, молоко, взбитые сливки</p>
                    <div class="details"><span class="volume">300 мл</span><span class="price">380</span></div>
                </div>
            </div>
            <div class="cocktail-card">
                <div class="cocktail-image">🍓</div>
                <div class="cocktail-info">
                    <h3>Клубничный</h3>
                    <p class="ingredients">Пломбир, молоко, клубничный сироп, взбитые сливки</p>
                    <div class="details"><span class="volume">300 мл</span><span class="price">380</span></div>
                </div>
            </div>
            <div class="cocktail-card">
                <div class="cocktail-image">🍍</div>
                <div class="cocktail-info">
                    <h3>Фруктовый</h3>
                    <p class="ingredients">Пломбир, сок в асс., взбитые сливки</p>
                    <div class="details"><span class="volume">300 мл</span><span class="price">490</span></div>
                </div>
            </div>
            <div class="cocktail-card">
                <div class="cocktail-image">🍫</div>
                <div class="cocktail-info">
                    <h3>Шоколадный</h3>
                    <p class="ingredients">Пломбир, молоко, какао, сироп, взбитые сливки</p>
                    <div class="details"><span class="volume">300 мл</span><span class="price">450</span></div>
                </div>
            </div>
        </div>
    </section>

    <!-- Безалкогольные коктейли -->
    <section class="category category-non-alcohol">
        <div class="category-title">🧃 Безалкогольные</div>
        <div class="cocktail-grid">
            <div class="cocktail-card">
                <div class="cocktail-image">🍊</div>
                <div class="cocktail-info">
                    <h3>Коктейль ФОРОС</h3>
                    <p class="ingredients">Сок апельсиновый, сок ананасовый, сироп банан, лимонный сок, безалкогольный ром</p>
                    <div class="details"><span class="volume">250 мл</span><span class="price">550</span></div>
                </div>
            </div>
            <div class="cocktail-card">
                <div class="cocktail-image">🌿</div>
                <div class="cocktail-info">
                    <h3>Мохито</h3>
                    <p class="ingredients">Лайм, мята, сахарный сироп, вода газированная</p>
                    <div class="details"><span class="volume">300 мл</span><span class="price">550</span></div>
                </div>
            </div>
            <div class="cocktail-card">
                <div class="cocktail-image">🥤</div>
                <div class="cocktail-info">
                    <h3>Сливочная кола</h3>
                    <p class="ingredients">Кола, мороженое, сироп</p>
                    <div class="details"><span class="volume">500 мл</span><span class="price">550</span></div>
                </div>
            </div>
            <div class="cocktail-card">
                <div class="cocktail-image">🍓</div>
                <div class="cocktail-info">
                    <h3>Ягодный заряд</h3>
                    <p class="ingredients">РЕД БУЛЛ арбуз, сироп черная смородина, лимонный сок, мята</p>
                    <div class="details"><span class="volume">300 мл</span><span class="price">650</span></div>
                </div>
            </div>
            <div class="cocktail-card">
                <div class="cocktail-image">🥥</div>
                <div class="cocktail-info">
                    <h3>Пина Колада</h3>
                    <p class="ingredients">Ананасовый сок, сливки, кокосовый сироп, взбитые сливки</p>
                    <div class="details"><span class="volume">300 мл</span><span class="price">550</span></div>
                </div>
            </div>
        </div>
    </section>

    <!-- Алкогольные коктейли (все в одной категории) -->
    <section class="category category-alcohol">
        <div class="category-title">🍹 Алкогольные</div>
        <div class="cocktail-grid">
            <!-- Апероль Спритц -->
            <div class="cocktail-card">
                <div class="cocktail-image">🍊</div>
                <div class="cocktail-info">
                    <h3>Апероль Спритц</h3>
                    <p class="ingredients">Ликер Апероль, игристое вино, вода газированная, апельсин</p>
                    <div class="details"><span class="volume">350 мл</span><span class="price">950</span></div>
                </div>
            </div>
            <!-- Фиеро Тоник -->
            <div class="cocktail-card">
                <div class="cocktail-image">🍸</div>
                <div class="cocktail-info">
                    <h3>Фиеро Тоник</h3>
                    <p class="ingredients">Мартини Фиеро, тоник, апельсин</p>
                    <div class="details"><span class="volume">400 мл</span><span class="price">750</span></div>
                </div>
            </div>
            <!-- Арбузный Джин -->
            <div class="cocktail-card">
                <div class="cocktail-image">🍉</div>
                <div class="cocktail-info">
                    <h3>Арбузный Джин</h3>
                    <p class="ingredients">РЕД БУЛЛ арбуз, Джин, сироп черная смородина, лимонный сок</p>
                    <div class="details"><span class="volume">350 мл</span><span class="price">660</span></div>
                </div>
            </div>
            <!-- Текила Санрайз (полный состав) -->
            <div class="cocktail-card">
                <div class="cocktail-image">🌅</div>
                <div class="cocktail-info">
                    <h3>Текила Санрайз</h3>
                    <p class="ingredients">Текила серебряная, сироп Гренадин, апельсиновый сок, апельсин</p>
                    <div class="details"><span class="volume">350 мл</span><span class="price">660</span></div>
                </div>
            </div>
            <!-- Бабл-гам -->
            <div class="cocktail-card">
                <div class="cocktail-image">🫧</div>
                <div class="cocktail-info">
                    <h3>Бабл-гам</h3>
                    <p class="ingredients">Ликер Банановый, ликер Амаретто, ликер Блю курасао, сливки, лимонный сок</p>
                    <div class="details"><span class="volume">150 мл</span><span class="price">550</span></div>
                </div>
            </div>
            <!-- Нью Йорк Булл (полный состав) -->
            <div class="cocktail-card">
                <div class="cocktail-image">🥤</div>
                <div class="cocktail-info">
                    <h3>Нью Йорк Булл</h3>
                    <p class="ingredients">Виски, Ред Булл классик, сироп черная смородина, лимонный сок, красное вино</p>
                    <div class="details"><span class="volume">200 мл</span><span class="price">650</span></div>
                </div>
            </div>
            <!-- Беллини -->
            <div class="cocktail-card">
                <div class="cocktail-image">🥂</div>
                <div class="cocktail-info">
                    <h3>Беллини</h3>
                    <p class="ingredients">Игристое, пюре персика, лимонный сок, сахарный сироп</p>
                    <div class="details"><span class="volume">200 мл</span><span class="price">550</span></div>
                </div>
            </div>
            <!-- Виски Кола -->
            <div class="cocktail-card">
                <div class="cocktail-image">🥤</div>
                <div class="cocktail-info">
                    <h3>Виски Кола</h3>
                    <p class="ingredients">Кола, виски, лимон</p>
                    <div class="details"><span class="volume">150 мл</span><span class="price">650</span></div>
                </div>
            </div>
            <!-- Маргарита -->
            <div class="cocktail-card">
                <div class="cocktail-image">🍋</div>
                <div class="cocktail-info">
                    <h3>Маргарита</h3>
                    <p class="ingredients">Текила серебряная, ликер Трипл Сек, сок лайма</p>
                    <div class="details"><span class="volume">300 мл</span><span class="price">750</span></div>
                </div>
            </div>
            <!-- Голубые Гавайи (полный состав) -->
            <div class="cocktail-card">
                <div class="cocktail-image">💙</div>
                <div class="cocktail-info">
                    <h3>Голубые Гавайи</h3>
                    <p class="ingredients">Малибу, ром белый, ликер Блю курасао, ананасовый сок, лимонный сок</p>
                    <div class="details"><span class="volume">200 мл</span><span class="price">650</span></div>
                </div>
            </div>
            <!-- Красная площадь -->
            <div class="cocktail-card">
                <div class="cocktail-image">🍓</div>
                <div class="cocktail-info">
                    <h3>Красная площадь</h3>
                    <p class="ingredients">Бехеровка, пюре малиновое, ванильный сироп, лимонный сок</p>
                    <div class="details"><span class="volume">300 мл</span><span class="price">550</span></div>
                </div>
            </div>
            <!-- Лимонный пирог -->
            <div class="cocktail-card">
                <div class="cocktail-image">🍋</div>
                <div class="cocktail-info">
                    <h3>Лимонный пирог</h3>
                    <p class="ingredients">Ликер Адвокат, ванильный сироп, водка, лимончелла, лимонный сок</p>
                    <div class="details"><span class="volume">350 мл</span><span class="price">650</span></div>
                </div>
            </div>
            <!-- Джин Тоник -->
            <div class="cocktail-card">
                <div class="cocktail-image">🍈</div>
                <div class="cocktail-info">
                    <h3>Джин Тоник</h3>
                    <p class="ingredients">Джин, тоник, лимон</p>
                    <div class="details"><span class="volume">300 мл</span><span class="price">750</span></div>
                </div>
            </div>
            <!-- Мохито (алкогольный) -->
            <div class="cocktail-card">
                <div class="cocktail-image">🌿</div>
                <div class="cocktail-info">
                    <h3>Мохито</h3>
                    <p class="ingredients">Ром белый, вода газированная, сахарный сироп, мята, лайм</p>
                    <div class="details"><span class="volume">400 мл</span><span class="price">950</span></div>
                </div>
            </div>
            <!-- Лонг Айленд -->
            <div class="cocktail-card">
                <div class="cocktail-image">🏝️</div>
                <div class="cocktail-info">
                    <h3>Лонг Айленд</h3>
                    <p class="ingredients">Джин, водка, ром белый, текила серебряная, ликер Трипл Сек, кола, лимонный сок</p>
                    <div class="details"><span class="volume">300 мл</span><span class="price">600</span></div>
                </div>
            </div>
            <!-- Куба Либре -->
            <div class="cocktail-card">
                <div class="cocktail-image">🥤</div>
                <div class="cocktail-info">
                    <h3>Куба Либре</h3>
                    <p class="ingredients">Ром черный, кола, сок лайма</p>
                    <div class="details"><span class="volume">200 мл</span><span class="price">650</span></div>
                </div>
            </div>
            <!-- Негронни -->
            <div class="cocktail-card">
                <div class="cocktail-image">🍊</div>
                <div class="cocktail-info">
                    <h3>Негронни</h3>
                    <p class="ingredients">Джин, ликер Кампари, Мартини Россо, апельсин</p>
                    <div class="details"><span class="volume">150 мл</span><span class="price">550</span></div>
                </div>
            </div>
            <!-- Кайперинья -->
            <div class="cocktail-card">
                <div class="cocktail-image">🍈</div>
                <div class="cocktail-info">
                    <h3>Кайперинья</h3>
                    <p class="ingredients">Кашаса, тростниковый сахар, лайм</p>
                    <div class="details"><span class="volume">150 мл</span><span class="price">550</span></div>
                </div>
            </div>
            <!-- Виски Сауэр -->
            <div class="cocktail-card">
                <div class="cocktail-image">🥚</div>
                <div class="cocktail-info">
                    <h3>Виски Сауэр</h3>
                    <p class="ingredients">Бурбон, белок яйца, лимонный сок, сахарный сироп</p>
                    <div class="details"><span class="volume">200 мл</span><span class="price">750</span></div>
                </div>
            </div>
            <!-- Глинтвейн -->
            <div class="cocktail-card">
                <div class="cocktail-image">🍷</div>
                <div class="cocktail-info">
                    <h3>Глинтвейн классический</h3>
                    <p class="ingredients">Красное вино, яблоко, апельсин, мед, специи</p>
                    <div class="details"><span class="volume">150 мл</span><span class="price">650</span></div>
                </div>
            </div>
        </div>
    </section>

    <div class="footer-note">
        Сканируй QR-код, чтобы всегда иметь меню под рукой
    </div>
</body>
</html>
