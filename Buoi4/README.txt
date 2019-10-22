if (p_AI->GetMyTeam() == TEAM_1) {
			//đây là team 1
			float x = tempTank->GetX();
			float y = tempTank->GetY();
			if (i == 0) {
				if(x<20)
					Game::CommandTank(i, DIRECTION_RIGHT, true, true);
				else
					Game::CommandTank(i, DIRECTION_UP, true, true);
			 
			}
			if (i == 1) {
				if (x < 20)
					Game::CommandTank(i, DIRECTION_RIGHT, true, true);
				else
					Game::CommandTank(i, DIRECTION_UP, true, true);

			}
			if (i == 2) {
				if (x < 20)
					Game::CommandTank(i, DIRECTION_RIGHT, true, true);
				else
					Game::CommandTank(i, DIRECTION_UP, true, true);

			}
			if (i == 3) {
				if (x < 20)
					Game::CommandTank(i, DIRECTION_RIGHT, true, true);
				else
					Game::CommandTank(i, DIRECTION_UP, true, true);

			}
		}
		else {
			// đây là team 2
			float x = tempTank->GetX();
			float y = tempTank->GetY();
			if (i == 0) {
				if (x > 1)
					Game::CommandTank(i, DIRECTION_LEFT, true, true);
				else
					Game::CommandTank(i, DIRECTION_DOWN, true, true);

			}
			if (i == 1) {
				if (x > 1 )
					Game::CommandTank(i, DIRECTION_LEFT, true, true);
				else
					Game::CommandTank(i, DIRECTION_DOWN, true, true);

			}
			if (i == 2) {
				if (x > 1)
					Game::CommandTank(i, DIRECTION_LEFT, true, true);
				else
					Game::CommandTank(i, DIRECTION_DOWN, true, true);

			}
			if (i == 3) {
				if (x >1)
					Game::CommandTank(i, DIRECTION_LEFT, true, true);
				else
					Game::CommandTank(i, DIRECTION_DOWN, true, true);

			}
		}
	}