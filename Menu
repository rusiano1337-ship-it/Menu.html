```html
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
            align-items: center;
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
        /* Цветовые акценты для категорий (можно менять) */
        .category-milk .cocktail-image { background: #f9e5d2; }  /* молочные */
        .category-non-alcohol .cocktail-image { background: #d7f0e6; } /* безалкогольные */
        .category-alcohol .cocktail-image { background: #d9e5f5; } /* алкогольные */
        .category-nybull .cocktail-image { background: #fde1d3; } /* нью-йорк булл */

        .cocktail-info {
            flex: 1;
        }
        .cocktail-info h3 {
            font-size: 1.2rem;
            font-weight: 600;
            margin-bottom: 4px;
            color: #1e1e1e;
            line-height: 1.3;
        }
        .ingredients {
            font-size: 0.85rem;
            color: #6f6f6f;
            margin-bottom: 8px;
            line-height: 1.4;
            display: -webkit-box;
            -webkit-line-clamp: 2;
            -webkit-box-orient: vertical;
            overflow: hidden;
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

    <!-- Категория: Молочные коктейли -->
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

    <!-- Категория: Безалкогольные коктейли -->
    <section class="category category-non-alcohol">
        <div class="category-title">🧃 Безалкогольные <span>разный объём</span></div>
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
                    <p class="ingredients">Колбашная кола, мороженое, сироп</p>
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
                    <p class="ingredients">Ананасовый сок, сливки, сахарный сироп, взбитые сливки</p>
                    <div class="details"><span class="volume">300 мл</span><span class="price">550</span></div>
                </div>
            </div>
        </div>
    </section>

    <!-- Категория: Алкогольные коктейли -->
    <section class="category category-alcohol">
        <div class="category-title">🍹 Алкогольные <span>разный объём</span></div>
        <div class="cocktail-grid">
            <div class="cocktail-card">
                <div class="cocktail-image">🍊</div>
                <div class="cocktail-info">
                    <h3>Апероль Спритц</h3>
                    <p class="ingredients">Ликер Апероль, игристое вино, вода газированная, апельсин</p>
                    <div class="details"><span class="volume">350 мл</span><span class="price">950</span></div>
                </div>
            </div>
            <div class="cocktail-card">
                <div class="cocktail-image">🍸</div>
                <div class="cocktail-info">
                    <h3>Фиеро Тоник</h3>
                    <p class="ingredients">Мартини Фиеро, тоник, апельсин</p>
                    <div class="details"><span class="volume">400 мл</span><span class="price">750</span></div>
                </div>
            </div>
            <div class="cocktail-card">
                <div class="cocktail-image">🍉</div>
                <div class="cocktail-info">
                    <h3>Арбузный Джин</h3>
                    <p class="ingredients">РЕД БУЛЛ арбуз, Джин, сироп черная смородина, лимонный сок</p>
                    <div class="details"><span class="volume">350 мл</span><span class="price">660</span></div>
                </div>
            </div>
            <div class="cocktail-card">
                <div class="cocktail-image">🌅</div>
                <div class="cocktail-info">
                    <h3>Текила Санрайз</h3>
                    <p class="ingredients">Текила серебряная, сироп гренландия, апельсин, апельсиновый сок</p>
                    <div class="details"><span class="volume">350 мл</span><span class="price">660</span></div>
                </div>
            </div>
            <div class="cocktail-card">
                <div class="cocktail-image">🫧</div>
                <div class="cocktail-info">
                    <h3>Бабл-гам</h3>
                    <p class="ingredients">Ликер Банановый, ликер Амаретто, ликер Блю кораса, сливки, лимонный сок</p>
                    <div class="details"><span class="volume">150 мл</span><span class="price">550</span></div>
                </div>
            </div>
        </div>
    </section>

    <!-- Категория: Нью Йорк Булл (и все последующие) -->
    <section class="category category-nybull">
        <div class="category-title">🥃 Нью Йорк Булл и другие</div>
        <div class="cocktail-grid">
            <div class="cocktail-card">
                <div class="cocktail-image">🥤</div>
                <div class="cocktail-info">
                    <h3>Нью Йорк Булл</h3>
                    <p class="ingredients">РЕД БУЛЛ классик, Виски, сироп черная смородина, лимонный сок, красное вино</p>
                    <div class="details"><span class="volume">200 мл</span><span class="price">650</span></div>
                </div>
            </div>
            <div class="cocktail-card">
                <div class="cocktail-image">🥂</div>
                <div class="cocktail-info">
                    <h3>Беллинг</h3>
                    <p class="ingredients">Игристое, пюре персика, лимонный сок, сахарный сироп</p>
                    <div class="details"><span class="volume">200 мл</span><span class="price">550</span></div>
                </div>
            </div>
            <div class="cocktail-card">
                <div class="cocktail-image">☕</div>
                <div class="cocktail-info">
                    <h3>Виски Коха</h3>
                    <p class="ingredients">Виски, кораллома, лимонный сок</p>
                    <div class="details"><span class="volume">150 мл</span><span class="price">650</span></div>
                </div>
            </div>
            <div class="cocktail-card">
                <div class="cocktail-image">🍋</div>
                <div class="cocktail-info">
                    <h3>Маргарита</h3>
                    <p class="ingredients">Текила серебряная, ликер Трипл Сек, сок лайма</p>
                    <div class="details"><span class="volume">300 мл</span><span class="price">750</span></div>
                </div>
            </div>
            <div class="cocktail-card">
                <div class="cocktail-image">💙</div>
                <div class="cocktail-info">
                    <h3>Голубые Гавайи</h3>
                    <p class="ingredients">Ликер Магнит, Ром белый, ликер Блю Кораса, ананасовый сок, лимонный сок</p>
                    <div class="details"><span class="volume">200 мл</span><span class="price">650</span></div>
                </div>
            </div>
            <div class="cocktail-card">
                <div class="cocktail-image">🍓</div>
                <div class="cocktail-info">
                    <h3>Красная площадь</h3>
                    <p class="ingredients">Березовая, малиновая пюре, ванильный сироп, лимонный сок</p>
                    <div class="details"><span class="volume">300 мл</span><span class="price">550</span></div>
                </div>
            </div>
            <div class="cocktail-card">
                <div class="cocktail-image">🍈</div>
                <div class="cocktail-info">
                    <h3>Джин Тоник</h3>
                    <p class="ingredients">Джин, тоник, лимон</p>
                    <div class="details"><span class="volume">300 мл</span><span class="price">750</span></div>
                </div>
            </div>
            <div class="cocktail-card">
                <div class="cocktail-image">🍳</div>
                <div class="cocktail-info">
                    <h3>Айчынный Пирот</h3>
                    <p class="ingredients">Ликер Адвохат, лимонный сок, ананасовый сироп, апельсинский сок</p>
                    <div class="details"><span class="volume">350 мл</span><span class="price">650</span></div>
                </div>
            </div>
            <div class="cocktail-card">
                <div class="cocktail-image">🌿</div>
                <div class="cocktail-info">
                    <h3>Мохито (алкогольный)</h3>
                    <p class="ingredients">Ром белый, вода газированная, сахарный сироп, мята, лайм</p>
                    <div class="details"><span class="volume">400 мл</span><span class="price">950</span></div>
                </div>
            </div>
            <div class="cocktail-card">
                <div class="cocktail-image">🏝️</div>
                <div class="cocktail-info">
                    <h3>Лонг Айленд</h3>
                    <p class="ingredients">Джин, Вода, Ром Белый, Текила серебряная, ликер Трипл Сек, кораллома, лимонный сок</p>
                    <div class="details"><span class="volume">300 мл</span><span class="price">600</span></div>
                </div>
            </div>
            <div class="cocktail-card">
                <div class="cocktail-image">🥤</div>
                <div class="cocktail-info">
                    <h3>Куба Либре</h3>
                    <p class="ingredients">Ром черный, кораллома, сок лайма</p>
                    <div class="details"><span class="volume">200 мл</span><span class="price">650</span></div>
                </div>
            </div>
            <div class="cocktail-card">
                <div class="cocktail-image">🍊</div>
                <div class="cocktail-info">
                    <h3>Негронни</h3>
                    <p class="ingredients">Джин, Ликер Кампар, Мартини Россо, апельсин</p>
                    <div class="details"><span class="volume">150 мл</span><span class="price">550</span></div>
                </div>
            </div>
            <div class="cocktail-card">
                <div class="cocktail-image">🍈</div>
                <div class="cocktail-info">
                    <h3>Кайперанья</h3>
                    <p class="ingredients">Каша, тростниковый сахар, лайм</p>
                    <div class="details"><span class="volume">150 мл</span><span class="price">550</span></div>
                </div>
            </div>
            <div class="cocktail-card">
                <div class="cocktail-image">🥚</div>
                <div class="cocktail-info">
                    <h3>Виски Сауэр</h3>
                    <p class="ingredients">Бурбон, белок яйца, лимонный сок, сахарный сироп</p>
                    <div class="details"><span class="volume">200 мл</span><span class="price">750</span></div>
                </div>
            </div>
            <div class="cocktail-card">
                <div class="cocktail-image">🍷</div>
                <div class="cocktail-info">
                    <h3>Глинтвейн Классический</h3>
                    <p class="ingredients">Красное вино, яблоко, апельсин, мед, специи</p>
                    <div class="details"><span class="volume">150 мл</span><span class="price">650</span></div>
                </div>
            </div>
        </div>
    </section>

    <div class="footer-note">
        ⚡ Сканируй QR-код, чтобы всегда иметь меню под рукой
    </div>
</body>
</html>
```
