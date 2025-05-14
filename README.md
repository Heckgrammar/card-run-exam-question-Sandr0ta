            int[] cards = new int[100];

            bool gameWon = false;

            for (int i = 0; i <= 95; i++)
            {
            
                if (cards[i + 1] == cards[i] + 1 &&
                    cards[i + 2] == cards[i] + 2 &&
                    cards[i + 3] == cards[i] + 3 &&
                    cards[i + 4] == cards[i] + 4)
                {
                    gameWon = true;
                    break;
